#  Grover's search - Part 1
**Algorithm Design**

In this tutorial, we will continue learning to develop quantum programs using QDE tools. This time, we'll implement a more complex algorithm: Grover's search algorithm for solving Boolean satisfiability (SAT) problems.

This tutorial consists of three parts that follow the typical workflow of developing and evaluating a quantum algorithm:

* In part 1, we will define generic Grover's search algorithm and the oracle for SAT problems and draw circuit diagrams for both using Circuit Designer.
* In part 2, we will implement the algorithm and test it using Workbench.
* Finally, in part 3, we will analyze the performance of our program using QRE Analyzer.

## Grover's search algorithm

Grover's search is often used as an example algorithm for showcasing quantum development tools. It is an algorithm for solving search problems defined as follows: We are given a function $f(x)$ that takes an $n$-bit bit string as an input and returns $0$ or $1$. The goal is to find an input $x_0$ for which this function returns $1$, or, in other words, to solve the equation $f(x) = 1$.

Grover's search is a generic algorithm: we can use it to solve any search problem, as long as we can implement two subroutines that describe the problem:

1. The mean state preparation.  
   The mean represents the search space of the problem. It is defined as the equal superposition of all basis states that correspond to valid inputs to $f(x)$.  

2. The phase oracle.  
   The oracle is a unitary that grants us access to the given function $f(x)$. We can apply it to any superposition state to evaluate the function on this state.

Given these two subroutines, Grover's algorithm implementation for a specific problem becomes straightforward:

1. Allocate $n$ qubits and prepare the mean state on them.

2. Apply several Grover iterations (the exact number of iterations is a parameter). Each iteration is the same and consists of two steps: applying the phase oracle followed by "reflection about the mean", a unitary defined as the following sequence of steps:

    1. Adjoint of the mean state preparation.

    2. "Reflection about  $| 0 \rangle$". This unitary can be implemented by applying an $X$ gate to each qubit, applying a controlled $Z$ gate to all qubits, and applying an $X$ gate to each qubit again.

    3. The mean state preparation.

3. Measure the qubits to get the result of the algorithm execution.

Let's start by drawing this algorithm as a generic quantum circuit diagram. Then, we'll talk about implementing it for our example of SAT problems.


## Drawing the circuit diagram: Grover's search

### 1. Create a circuit

Create a new circuit in Circuit Designer. Give it a descriptive title, for example, `Grover's search algorithm`. (You can remove the copyright by unchecking *Show Copyright* checkbox.)


### 2. Define circuit register

Grover's search acts on a qubit register `x` with a variable number of rails. The circuit diagram is created with one register by default. We can customize it by choosing *Rail Labels* to be `Custom` and setting *Rail Names* to `0,...,n-1` to emphasize that this is a multi-qubit register.

The qubits of the register should be initialized in the $|0\rangle$ state. We can express that by using a `write` gate with *Target Rails* set to `x`.

At this point, the diagram will look like this:

![Step 2: define circuit register](./circuits/grover-step2-registers.svg)


### 3. Define the main routines

Grover's search consists of three main routines that we will create on this step:

1. Initial mean state preparation.
2. Phase oracle.
3. Reflection about the mean.

These routines all act on *Target Rails* `x`.

> Notice that you can use LaTeX when defining the routine labels. For example, if you want to label the first routine "Mean state prep", with each word centered on a separate line, you can use the following LaTeX snippet:
>
> ```
> \begin{gather}
> \text{Mean} \\
> \text{state} \\
> \text{prep}
> \end{gather}
> ```

Additionally, we need to denote that the last two routines, the phase oracle and reflection about the mean, together represent one logical step - Grover iteration - and should be repeated several times. We can do that by adding a group labeled `\text{Grover iteration - repeat K times}` to the diagram and dragging the routines inside it.

Unlike the routines, the groups cannot be collapsed or expanded; they allow us to group and annotate related routines. By default, the groups have neither background nor border; we can modify the appearance of the Grover iteration group by setting *Border* to `dashed`.

The last step of the algorithm is the final measurement, which we can express as a `measure` gate, also acting on *Target Rails* `x`.

The resulting diagram will look like this:

![Step 3: define routines](./circuits/grover-step3-routines.svg)


### 4. Define reflection about the mean

Next, we need to implement reflection about the mean.
This routine consists of three subroutines:

1. Adjoint of the mean state preparation.
2. Reflection about the $|0\rangle$ state.
3. Mean state preparation.

For readability, you can change the routine "Reflection about the mean" to show its label above the routine rather than on the left by choosing `Above` in the *When Expanded* dropdown.

After adding these subroutines and naming them, the diagram will look like this:

![Step 4: reflection about the mean](./circuits/grover-step4-mean-reflection.svg)


### 5. Define reflection about $|0\rangle$

The last routine we can implement while keeping the circuit diagram generic is reflection about the $|0\rangle$ state.
This routine consists of the following sequence of steps:

1. Apply an $X$ gate to each qubit. We can show this by adding an `x` gate with *Target Rails* set to `x`.
2. Apply a controlled $Z$ gate acting on all qubits. Since all qubits are treated the same by this gate, we don't want to emphasize one of them as the target of the gate. To reflect this on the diagram, we can use a `z` gate with *Target Rails* set to an empty string and *Control Rails* set to `x`.
3. Apply an $X$ gate to each qubit again, same as the first step.

The final diagram will look as follows:

![Step 5: reflection about zero](./circuits/grover-step5-zero-reflection.svg)


## Subroutines for solving SAT problems

Our goal in this tutorial is to use Grover's algorithm to solve Boolean satisfiability (SAT) problems. A SAT problem is defined using a Boolean formula $f(x)$ that acts on $n$ Boolean variables. An example of a Boolean formula with three variables is

$$f(x_0, x_1, x_2) = (x_0 \lor x_1) \land (x_0 \lor \neg x_2)$$

Any $n$-bit string is a valid input to the function, so the mean state used in Grover's algorithm is just an equal superposition of all $n$-qubit basis states. We can prepare this state by applying a Hadamard gate to each qubit.

> We'll skip drawing the circuit diagram for the mean state preparation for SAT problems, since it is so simple.

Implementing the quantum oracle for SAT problems is more interesting, and this will be our focus for the second half of this tutorial.
Grover's search relies on the implementation of the function $f(x)$ as a phase oracle $U_p$, defined as follows:

$$U_p \sum_x a_x |x\rangle = \sum_x (-1)^{f(x)} a_x |x\rangle$$

In practice, it is often easier to implement the function as a marking oracle using an extra "output" qubit $|y\rangle$ to store the function value:

$$U_m \sum_{x,y} a_x |x\rangle |y\rangle = \sum_{x,y} a_x |x\rangle |y \oplus f(x)\rangle$$

Then we can convert the marking oracle to a phase oracle using the phase kickback trick. Applying the marking oracle to an input register in an arbitrary state and the output qubit in the state $|-\rangle$ has the same effect as applying the phase oracle to the input register:

$$U_m \left( \sum_{x} a_x |x\rangle |-\rangle \right) = \left( U_p \sum_{x} a_x |x\rangle \right) |-\rangle$$

> Phase kickback trick is very straightforward, so we'll skip drawing the circuit diagram for it as well.

How can we implement the marking oracle for a general SAT formula, given that formula?

1. We'll need to allocate several auxiliary qubits, one for each clause of the formula.
2. Then, we can evaluate each clause as an OR of several input variables or their negations and store the evaluation result in the corresponding auxiliary qubit.
3. Next, we can evaluate the formula itself as an AND of all clauses using the auxiliary qubits as inputs.
4. Finally, we'll need to uncompute the clauses evaluation before releasing the auxiliary qubits.

Let's see what this sequence of steps will look like as a circuit diagram for our example formula.


## Drawing the circuit diagram: SAT problems oracle

### 1. Create a circuit

Create a new circuit in Circuit Designer. Give it a descriptive title, for example, `Marking oracle for f(x) = (x₀ ∨ x₁) ∧ (x₀ ∨ ¬x₂)`.

> Note that you can't use LaTeX in diagram title, but you can use Unicode!

### 2. Define circuit registers and the main routines

The marking oracle uses three qubit registers: the input variables $x$, the output qubit $y$, and the auxiliary qubits $a$. Let's go ahead and define them.

Since we're drawing the circuit for a fixed SAT formula, each register will have a fixed number of rails: three qubits in $x$, two in $a$, and one in $y$. We can change the number of rails in registers $x$ and $a$ by setting *Rail Labels* to `Custom` and defining *Rail Names* as `x_0,x_1,x_2` and `a_0,a_1`, respectively. We'll use these rail names when labeling the routines as well.

The qubit registers $x$ and $y$ can be passed to the oracle in any state, but the register $a$ is allocated by the oracle itself and initialized in the $|0\rangle$ state. We can emphasize that by using a `write` gate with *Target Rails* set to `a`.

Finally, let's add the three routines that correspond to the main steps of the oracle evaluation: compute the clauses (named `compute`), compute the result (`result`), and uncompute the clauses (`uncompute`). You can modify routine names by double-clicking on it in the left panel. The first and the last routines should act on `x,a` as *Target Rails*, and the second routine - on `a,y`.

At this point, the diagram will look like this:

![Step 2: define circuit registers and routines](./circuits/oracle-step2-registers.svg)


### 3. Define the "compute clauses" routine

Next, we need to define the circuit that computes the clauses and its counterpart that uncomputes the clauses.

Our example formula has two clauses, and we'll evaluate each of them separately, using a subset of qubits in the register $x$ as the input and one of the qubits in the register $a$ as the target.

We can show this on the diagram as two subroutines acting on different sets of qubits within the `compute` parent routine:

1. The routine for the first clause `clause0` will have *Label* `x_0 \lor x_1` and act on *Target Rails* `x[0],x[1],a[0]`.
2. The routine for the second clause `clause1` will have *Label* `x_0 \lor \neg x_2` and act on *Target Rails* `x[0],x[2],a[1]`.

The `uncompute` routine will consist of the same subroutines: since the evaluation of the clauses is reversible, its adjoint equals itself. If we want to emphasize the uncomputation aspect of the circuit, we can swap the subroutines, so that the clause that was computed last is uncomputed first.

![Step 3: "compute clauses" routine](./circuits/oracle-step3-clauses.svg)


### 4. Gate-level routines definition

On the last step, we'll break down our routines for computing the clauses and the result into sequences of gates.

Each individual clause computation and uncomputation routine is an OR of the corresponding subset of input qubits. We can express this using two gates: an $X$ gate with a subset of input qubits as controls and the corresponding auxiliary qubit as the target, followed by an $X$ gate on the auxiliary qubit.

1. For the first clause, $x_0 \lor x_1$, *Target Rails* of the controlled $X$ gate will be `a[0]` and *Control Rails* - `~x[0],~x[1]`.
2. For the second clause, $x_0 \lor \neg x_2$, *Target Rails* of the controlled $X$ gate will be `a[1]` and *Control Rails* - `~x[0],x[2]`.

When we define the gates that are part of the `uncompute` routine, we can again emphasize the uncomputation by swapping the order of the gates in each clause evaluation compared to that within the `compute` routine and placing the $X$ gates before controlled $X$ gates.

Finally, we can compute the result as the AND of the auxiliary qubits. To express this, we add an $X$ gate to the `result` routine, with *Target Rails* set to `y` and *Control Rails* set to `a`.

The final circuit diagram of the marking oracle will look as follows:

![Step 4: gate-level definition](./circuits/oracle-step4-gates.svg)


## Conclusion

In this tutorial,

* We defined Grover's search algorithm and designed the circuit diagram for it.
* We discussed applying Grover's algorithm to solving SAT problems and the necessary building blocks for it.
* Finally, we defined the implementation of the quantum oracle - the most complicated part of implementing Grover's algorithm for a specific problem - and designed the circuit diagram for the marking oracle for a small example of a SAT problem.

In the [next part of this tutorial](satsolver_code.ipynb), we will implement this algorithm in Workbench and test that our implementation is correct!
