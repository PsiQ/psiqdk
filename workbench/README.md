# PsiQ Workbench

**Workbench** is a Python framework for writing, simulating, and resource-estimating quantum programs. It pairs a programmer-centric Python API with an optimized multi-threaded C++ simulation backend, and the same API is designed to one day target PsiQuantum's photonic QPU.

This folder contains the **public tutorial notebooks** that accompany the official Workbench documentation.

## Highlights

- **Fast** - a multi-CPU-optimized native simulator written in C++.
- **Programmer-centric** - a Python API co-designed by quantum researchers and software engineers, with familiar control flow, data types, and abstractions.
- **Extensible** - modular pipeline for snap-on compilation and analysis steps.
- **Fully-featured** - elementary gates, controlled and multi-controlled operations, measurements, classical control, arithmetic, and the [Qubricks](https://open-docs.construct.psiquantum.com/) framework for structured qubit management and uncomputation.
- **Resource estimation built in** - get symbolic and numeric estimates of the resources required to run a program on fault-tolerant hardware.

## Documentation

Full documentation: <https://open-docs.construct.psiquantum.com/>

## Installation

Workbench ships as part of [PsiQDK](../README.md):

```bash
pip install psiqdk
```

Workbench is then available under the `psiqdk.workbench` namespace:

```python
from psiqdk.workbench import QPU
```

## Tutorials

The [`tutorials/`](./tutorials) directory contains runnable Jupyter notebooks covering the full breadth of Workbench. They are organized below by topic.

### Getting started

| Notebook | Description |
| --- | --- |
| [Basic-Gates.ipynb](./tutorials/Basic-Gates.ipynb) | Single-qubit gates and the basics of building a circuit. |
| [Controlled-Gates.ipynb](./tutorials/Controlled-Gates.ipynb) | Controlled and multi-controlled operations. |
| [Advanced-Gates.ipynb](./tutorials/Advanced-Gates.ipynb) | Higher-level gate constructs and patterns. |
| [Measurements.ipynb](./tutorials/Measurements.ipynb) | Measurement operations and classical outcomes. |
| [QPU-Object.ipynb](./tutorials/QPU-Object.ipynb) | The `QPU` object: lifecycle, state, and execution. |
| [Qubits-Data-Type.ipynb](./tutorials/Qubits-Data-Type.ipynb) | Working with qubits and qubit registers as first-class values. |

### Simulation, execution, and debugging

| Notebook | Description |
| --- | --- |
| [Simulating-WB-Programs.ipynb](./tutorials/Simulating-WB-Programs.ipynb) | Running Workbench programs in simulation. |
| [Configuring-Execution.ipynb](./tutorials/Configuring-Execution.ipynb) | Tuning the simulator and selecting execution modes. |
| [Testing-Debugging.ipynb](./tutorials/Testing-Debugging.ipynb) | Patterns for writing tests and debugging quantum programs. |

### Qubricks - structured qubit management

| Notebook | Description |
| --- | --- |
| [Qubricks.ipynb](./tutorials/Qubricks.ipynb) | Introduction to the Qubricks framework. |
| [Built-in-Qubricks.ipynb](./tutorials/Built-in-Qubricks.ipynb) | A tour of the built-in Qubrick library. |
| [Qubricks-Qubit-Management.ipynb](./tutorials/Qubricks-Qubit-Management.ipynb) | Allocating, scoping, and releasing qubits. |
| [Qubricks-Controlled.ipynb](./tutorials/Qubricks-Controlled.ipynb) | Building controlled Qubricks. |
| [Qubricks-Uncomputation.ipynb](./tutorials/Qubricks-Uncomputation.ipynb) | Uncomputation patterns and ancilla cleanup. |
| [Qubricks-Computed-Context-Manager.ipynb](./tutorials/Qubricks-Computed-Context-Manager.ipynb) | The `computed` context manager for safe scratch use. |

### Quantum arithmetic

| Notebook | Description |
| --- | --- |
| [Quantum-Arithmetic.ipynb](./tutorials/Quantum-Arithmetic.ipynb) | Arithmetic on quantum registers. |
| [Quantum-Arithmetic-Data-Types.ipynb](./tutorials/Quantum-Arithmetic-Data-Types.ipynb) | Integer and fixed-point quantum data types. |
| [QRE-Analysis-for-Arithmetic-Variants.ipynb](./tutorials/QRE-Analysis-for-Arithmetic-Variants.ipynb) | Comparing resource costs across arithmetic implementations. |

### Resource estimation

| Notebook | Description |
| --- | --- |
| [Resource-Estimates-Basic-Numerics.ipynb](./tutorials/Resource-Estimates-Basic-Numerics.ipynb) | Numerical resource estimates for fault-tolerant execution. |

## Validating your installation

Run the following Python snippet to confirm Workbench is installed correctly:

```python
from psiqdk.workbench import QPU

qpu = QPU(num_qubits=2)
qpu.print_state_vector()
```

Expected output:

```text
State vector:
  |0> (1, 0)
```

## Feedback

Report issues at <https://github.com/PsiQ/psiqdk/issues/new/>.
