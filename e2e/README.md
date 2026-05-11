# End-to-end examples

End-to-end tutorials that walk through the **complete workflow** for developing a fault-tolerant quantum program with PsiQDK:

1. **Algorithm design** - sketch the algorithm and draw its circuit using Circuit Designer.
2. **Implementation** - implement the algorithm in [Workbench](../workbench) and verify it via simulation.
3. **Resource estimation** - analyze the cost of running the program on a fault-tolerant quantum computer.

Each example is split into the three parts above so you can follow the same flow you would use for your own work.

## Documentation

Full documentation: <https://open-docs.construct.psiquantum.com/>

## Prerequisites

These examples assume an installed PsiQDK environment:

```bash
pip install psiqdk
```

## Examples

The [`tutorials/`](./tutorials) directory contains the following end-to-end examples.

### Recursive quantum state preparation

A textbook recursive algorithm that prepares an arbitrary real-amplitude state on `n` qubits.

| Part | Notebook / file | Topic |
| --- | --- | --- |
| 1 | [stateprep_circuit.md](./tutorials/stateprep_circuit.md) | Algorithm design and circuit diagram. |
| 2 | [stateprep_code.ipynb](./tutorials/stateprep_code.ipynb) | Workbench implementation and simulation. |
| 3 | [stateprep_qre_analysis.ipynb](./tutorials/stateprep_qre_analysis.ipynb) | Resource estimation and analysis. |

### Grover's search for SAT

Grover's search algorithm applied to Boolean satisfiability (SAT) problems, with a custom oracle.

| Part | Notebook / file | Topic |
| --- | --- | --- |
| 1 | [satsolver_circuit.md](./tutorials/satsolver_circuit.md) | Algorithm design and circuit diagram. |
| 2 | [satsolver_code.ipynb](./tutorials/satsolver_code.ipynb) | Workbench implementation and simulation. |
| 3 | [satsolver_qre.ipynb](./tutorials/satsolver_qre.ipynb) | Resource estimation and analysis. |

Supporting circuit diagrams and media live under [`tutorials/circuits/`](./tutorials/circuits) and [`tutorials/media/`](./tutorials/media).

## Feedback

Report issues at <https://github.com/PsiQ/psiqdk/issues/new/>.
