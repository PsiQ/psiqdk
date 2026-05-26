# End-to-end examples

End-to-end tutorials that walk through the **complete workflow** for developing a fault-tolerant quantum program with PsiQDK:

1. **Algorithm design** - sketch the algorithm and draw its circuit using [Circuit Designer](https://circuits.psiquantum.com/).
2. **Implementation** - implement the algorithm in [Workbench](../workbench) and verify it via simulation.
3. **Resource estimation** - analyze the cost of running the program on a fault-tolerant quantum computer.

Each example is split into several parts, following the same workflow one would use for quantum application development.

## Documentation

[End-to-end tutorials](https://open-docs.construct.psiquantum.com/construct/tutorials/stateprep_circuit.html).

## Prerequisites

These examples assume an installed PsiQDK environment:

```bash
pip install psiqdk
```

## Examples

The [`tutorials/`](./tutorials) directory contains the following end-to-end examples:

* Quantum state preparation - a textbook recursive algorithm that prepares an arbitrary multi-qubit state with real amplitudes.
* Grover's search algorithm for solving Boolean satisfiability (SAT) problems.

You can find the supporting circuit diagrams for the tutorials under [`tutorials/circuits/`](./tutorials/circuits).

## Getting help

Please [file an issue](https://github.com/PsiQ/psiqdk/issues/new/) to report a bug or to request a feature, or [start a discussion](https://github.com/PsiQ/psiqdk/discussions/new/choose) to ask a question.
