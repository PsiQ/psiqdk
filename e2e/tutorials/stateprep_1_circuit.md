# Quantum State Prep - Part 1
**Algorithm Design**

In this tutorial, we will learn to create a quantum program using Construct.

This tutorial consists of three parts that follow the typical workflow of developing and evaluating a quantum algorithm:

* In part 1, we will define the algorithm we'll be working on and draw a circuit diagram for it using [Circuit Designer](https://circuits.psiquantum.com/).
* In part 2, we will implement the algorithm and test it using Workbench.
* Finally, in part 3, we will analyze the performance of our program using Resource Analyzer.

## Quantum state preparation algorithm

Quantum state preparation is an important primitive in quantum algorithms. The problem is formulated as follows: We are given a register of $n$ qubits in the $|0\rangle$ state and a list of $2^n$ real amplitudes $a$. The goal is to prepare the state described by these amplitudes on this qubit register: $a_0|0\rangle + a_1|1\rangle + ... + a_{2^n-1} |2^n-1\rangle$.

> We will use little-endian to map bit strings to integers in basis states representations: basis state $|10\rangle$ will be written as $|1\rangle$, and $|01\rangle$ - as $|2\rangle$. This convention matches the one used by Workbench, so this will be convenient when we get to the second part of the tutorial, implementing the algorithm using Workbench.

Throughout this tutorial, we'll implement a straightforward recursive algorithm for solving this task.

For $n = 1$, we can convert $|0\rangle$ to $a_0|0\rangle + a_1|1\rangle$ using an $Ry$ gate with an appropriate rotation angle. This is the base case of recursion.

For $n = 2$, we can prepare the state $a_0|00\rangle + a_1|10\rangle + a_2|01\rangle + a_3|11\rangle$ in three steps:

1. Prepare the first qubit in the state $\sqrt{a_0^2 + a_2^2}|0\rangle + \sqrt{a_1^2 + a_3^2}|1\rangle$.
2. Use controlled-on-zero single-qubit state preparation routine to change the first term of the two-qubit state from $\sqrt{a_0^2 + a_2^2}|0\rangle \otimes |0\rangle$ to $a_0|00\rangle + a_2|01\rangle$.
3. Use controlled-on-one single-qubit state preparation routine to change the second term of the two-qubit state from $\sqrt{a_1^2 + a_3^2}|1\rangle \otimes |0\rangle$ to $a_1|10\rangle + a_3|11\rangle$.

Finally, if we know how to prepare an arbitrary state on $n-1$ qubits, we can use this as a building block for preparing the given state on $n$ qubits similarly:

1. Start by preparing one of the qubits (the least significant one) in the correct superposition state.
2. Then, adjust the states of the remaining $n-1$ qubits using two calls to the $n-1$-qubit state preparation routine with the first qubit as the control: one call with the routine controlled-on-zero and the other - with the routine controlled-on-one.

Let's start by expressing this algorithm as a quantum circuit diagram.

> You can find the complete circuit diagram for recursive state preparation built in this tutorial [in Circuit Designer](https://construct.psiquantum.com/cd/https://github.com/PsiQ/circuit-hub/raw/main/psiq-tutorial-circuits/recursive-state-preparation.circuit.json).

## Drawing the circuit diagram

### 1. Create a circuit

Create a new circuit in Circuit Designer. Give it a descriptive title, for example, `Recursive state preparation SPₙ`.


### 2. Define circuit registers and the main routine

The algorithm splits the qubits into two groups: the least significant qubit (LSQ) and the remaining $n-1$ most significant qubits (MSQ). To reflect this, let's define two qubit registers:

1. One-qubit register LSQ.  
Registers are created with one qubit by default, so we only need to set *ID* to `LSQ` and *Label* to `\text{LSQ}`.
2. Multi-qubit register MSQ.  
Start by setting *ID* to `MSQ` and *Label* to `\text{MSQ}`. The algorithm acts on a variable number of qubits, so we need a way to show that on the diagram. Let's show four rails, two most significant and two least significant, and denote the variable number of rails between them with ellipsis. To do this, choose `Custom` from the *Rail Labels* dropdown and type `1,2,...,n-2,n-1` in the *Rail Names*. The register consisting of multiple rails will be expanded by default, showing the individual rails labeled with their names.

> Notice that with this definition the register MSQ will have five rails named $1$, $2$, $...$, $n-2$ and $n-1$. We will use this later, when we define which rails the various gates act on.

Next, let's emphasize that this algorithm assumes that the qubit register passed to it as an argument is initialized in the $|0\rangle$ state. To do this, we can add a `write` gate to the circuit and set *Target Rails* to `LSQ,MSQ` to initialize all qubits.

Finally, let's add the main state preparation routine $\text{SP}_n$: add a new routine, type `\text{SP}_n` in the *Label* field and `LSQ,MSQ` in the *Target Rails* field to have it act on all qubits.

![Step 2: define circuit registers](./circuits/stateprep-step2-registers.svg)


### 3. Define top-level routines

The state preparation routine $\text{SP}_n$ consists of three steps: preparing the least significant qubit in the correct state using the single-qubit variant of our state preparation routine, $\text{SP}_1$, and then calling two variants of controlled-$\text{SP}_{n-1}$ to adjust the state of the most significant qubits. Let's add these routines to the diagram within the $\text{SP}_n$ routine.

1. Prepare the least significant qubit.  
Add a new routine, type `\text{SP}_1` in the *Label* field and `LSQ` in the *Target Rails* field.
2. Adjust the state of the most significant qubits.  
We need two controlled routines here, both with LSQ acting as the control register and MSQ - as the target register.  
Add a new routine, type `\text{SP}_{n-1}` in the *Label* field, `MSQ` in the *Target Rails* field, and `~LSQ` in the *Control Rails* field. Setting this last field makes the routine controlled, and using `~` before the register name makes it controlled-on-zero.  
Repeat the process for the second controlled routine, this time using `LSQ` in the *Control Rails* field to make the routine controlled-on-one.

> When a new routine is added to the circuit, it will be created as the rightmost element inside the currently selected routine. When you create the routines inside $\text{SP}_n$, make sure you have $\text{SP}_n$ selected.

By default, when you expand a routine which has other elements inside it, its label will move to the left side of that routine and rotate $90^\circ$ counterclockwise. In our case, the diagram will have multiple layers of nested routines. To keep it from growing too wide, we can move the label of each expanded routine to the top by choosing `Above` in the *When Expanded* dropdown.

With these three routines added, the diagram will look like this:

![Step 3: define top-level routines](./circuits/stateprep-step3-top-level.svg)

We can collapse the $\text{SP}_n$ routine to show the diagram without its implementation, the way it looked on the previous step.


### 4. Next step of recursion

Now, let's show the next step of recursion by populating the left $\text{SP}_{n-1}$ routine with the three routines that comprise it: another $\text{SP}_1$ and two controlled $\text{SP}_{n-2}$ routines. We'll keep the right $\text{SP}_{n-1}$ routine as is to reduce the overall size of circuit, implying that it behaves similarly to its neighbor.

> Notice that when we expand a controlled $\text{SP}_{n-1}$ routine in Circuit Designer, it still shows its control register (in this case, LSQ). However, we'll add LSQ to the controls of each of its subroutines of $\text{SP}_{n-1}$ to clearly emphasize that the deeper the subroutine is, the more control qubits it has.

The new routines will be similar to those added on the previous step, but they will have different control and target registers:

1. The $\text{SP}_1$ routine will have `MSQ[0]` as *Target Rails* and `~LSQ` as *Control Rails*.
2. The first $\text{SP}_{n-2}$ routine will have `MSQ[1:]` as *Target Rails*, to denote all qubits in MSQ except the first one, and `~LSQ,~MSQ[0]` as *Control Rails*.
3. The second $\text{SP}_{n-2}$ routine will have `MSQ[1:]` as *Target Rails* as well, and `~LSQ,MSQ[0]` as *Control Rails*. (Notice the difference in the second bit of control patterns between the two $\text{SP}_{n-2}$ routines.)

Now, the circuit diagram looks like this:

![Step 4: next level of recursion](./circuits/stateprep-step4-next-level.svg)

However, if we collapse the left $\text{SP}_{n-1}$ routine, its implementation details will be hidden, and the diagram will look the way it looked after the previous step.


### 5. Second-to-last step of recursion

Our diagram has five visible rails, so it should end up representing the algorithm for preparing a five-qubit state. In this case, the next step will be the second-to-last step of recursion, on which we apply $\text{SP}_2$ routines (with appropriate control patterns) to the two most significant qubits.

Same as on the previous step, we'll detail the implementation of the left $\text{SP}_{n-2}$ routine, leaving the right one unchanged. We'll need to create three new routines:

1. $\text{SP}_1$ routine will have `MSQ[1]` as *Target Rails* and `~LSQ,~MSQ[0]` as *Control Rails*.
2. The first $\text{SP}_2$ routine will have `MSQ[3:]` as *Target Rails*, to denote all qubits in MSQ except the first two, and `~LSQ,~MSQ[0:2]` as *Control Rails*.
3. The second $\text{SP}_2$ routine will have `MSQ[3:]` as *Target Rails* as well, and `~LSQ,~MSQ[0],MSQ[1]` as *Control Rails*. (Again, the difference in control patterns between the two $\text{SP}_2$ routines is only in the most significant of the control qubits.)

We can add a separator of type `Ellipsis` here between the two $\text{SP}_2$ routines to denote that for state preparation routines acting on more qubits there will be more steps here and more such routines. When adding the separator, change *Separator Covers Rails* to `MSQ[2]` to align it with the middle rail of the register MSQ (the one denoted with the vertical ellipsis).

![Step 5: second-to-last level of recursion](./circuits/stateprep-step5-second-to-last-level.svg)


### 6. Last step of recursion

The last step of recursion is applying $\text{SP}_1$ routines (with appropriate control patterns) to the most significant qubits. On this step, let's add complete implementations to both $\text{SP}_2$ routines (six routines total). This will help us illustrate the control patterns of $\text{SP}_1$ routines.

The process of adding new routines is very similar to what we did on the previous steps. Keep an eye on the control patterns for each $\text{SP}_1$ routine as you copy-paste them to make sure they are all unique.

The resulting diagram will look as follows:

![Step 6: second-to-last level of recursion](./circuits/stateprep-step6-sp1-level.svg)


### 7. Rotation gates

Now that our diagram shows the complete recursive structure of the algorithm, we need to clarify how it translates into actual quantum gates. To do this, we can add an $Ry$ gate to each $\text{SP}_1$ routine. Each $Ry$ gate will have the same input and Control Rails as the $\text{SP}_1$ routine it implements to make sure expanding the routines maintains the correct structure of controls.

With the $Ry$ gates added and all $\text{SP}_1$ routines expanded, the diagram will look as follows:

![Step 7: rotation gates](./circuits/stateprep-step7-ry-gates.svg)


### 8. Readability improvements

At this point, the diagram conveys all the information about the structure of the algorithm it can. (The details such as the rotation angles for each gate are out of scope for a circuit diagram.)

We can, however, tweak the appearance of the diagram to improve its readability. There are a lot of nested routines in this circuit, and it can be tricky to figure out which routine belongs to which box at a glance.

To group the routines at different levels of recursion together, we can change their *Label Color* (in the *Routine Properties* section) and *Border Color* (in the *Appearance* section).
The top-level routine $\text{SP}_n$ will use one of the built-in colors (for example, `lime`), the routines inside it (the first $\text{SP}_1$ and the two $\text{SP}_{n-1}$) - a slightly darker color (`green`), and so on, the deeper the routine, the darker its color, until the final six $\text{SP}_1$ routines will use `purple`.

The result will look similar to this diagram:

![Step 8: readability improvements](./circuits/stateprep-step8-readability.svg)


## Conclusion

In this tutorial, we explored the structure of the recursive state preparation algorithm and designed its circuit diagram using Circuit Designer.

In the [next part of this tutorial](./stateprep_2_code.ipynb), we will implement this algorithm in Workbench and test that our implementation is correct!

