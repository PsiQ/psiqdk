# Algorithms

**Algorithms** is a library of reusable quantum-algorithm primitives and subroutines built on top of [Workbench](../workbench). It provides production-quality implementations of the building blocks that appear in almost every fault-tolerant quantum algorithm - state preparation, amplitude amplification, phase estimation, QROM-based data loading, quantum arithmetic, and more - each accompanied by symbolic resource estimates.

This folder contains the **public tutorial notebooks** for the library.

## Documentation

Full documentation: <https://open-docs.construct.psiquantum.com/>

## Installation

Algorithms ships as part of [PsiQDK](../README.md):

```bash
pip install psiqdk
```

The library is then available under the `psiqdk.algorithms` namespace:

```python
from psiqdk.algorithms import ...
```

## Tutorials

The [`tutorials/`](./tutorials) directory contains runnable Jupyter notebooks. They are organized below by topic.

### State preparation

| Notebook | Description |
| --- | --- |
| [Naive_state_preparation_tutorial.ipynb](./tutorials/Naive_state_preparation_tutorial.ipynb) | A straightforward recursive state-preparation method. |
| [Uniform_state_preparation_tutorial.ipynb](./tutorials/Uniform_state_preparation_tutorial.ipynb) | Preparing uniform superpositions over arbitrary ranges. |
| [Multiplexed_USP.ipynb](./tutorials/Multiplexed_USP.ipynb) | Multiplexed uniform state preparation. |
| [Alias_sampling_tutorial.ipynb](./tutorials/Alias_sampling_tutorial.ipynb) | State preparation via alias sampling. |
| [Low_Kliuchnikov_Schaeffer_state_preparation_tutorial.ipynb](./tutorials/Low_Kliuchnikov_Schaeffer_state_preparation_tutorial.ipynb) | The Low–Kliuchnikov–Schaeffer state-preparation method. |
| [Window_states_for_QPE_tutorial.ipynb](./tutorials/Window_states_for_QPE_tutorial.ipynb) | Preparing window states used in quantum phase estimation. |

### Phase estimation and amplitude amplification

| Notebook | Description |
| --- | --- |
| [Quantum_phase_estimation_tutorial.ipynb](./tutorials/Quantum_phase_estimation_tutorial.ipynb) | Standard quantum phase estimation. |
| [Iterative_Quantum_Phase_Estimation.ipynb](./tutorials/Iterative_Quantum_Phase_Estimation.ipynb) | Iterative phase estimation with reduced ancilla count. |
| [Amplitude_Amplification.ipynb](./tutorials/Amplitude_Amplification.ipynb) | Generic amplitude amplification (Grover-style). |

### LCU, qubitization, and Hamiltonian simulation

| Notebook | Description |
| --- | --- |
| [LCU_Qubitization.ipynb](./tutorials/LCU_Qubitization.ipynb) | Linear combination of unitaries and qubitization. |
| [Trotterization_tutorial.ipynb](./tutorials/Trotterization_tutorial.ipynb) | Trotter–Suzuki decomposition for Hamiltonian simulation. |
| [Dyson_Series_Expansion_Tutorial.ipynb](./tutorials/Dyson_Series_Expansion_Tutorial.ipynb) | Time-dependent Hamiltonian simulation via the Dyson series. |
| [PauliMasks_and_PauliSums_tutorial.ipynb](./tutorials/PauliMasks_and_PauliSums_tutorial.ipynb) | Working with Pauli masks and Pauli sums. |
| [Majorana_Fermion_Operator_tutorial.ipynb](./tutorials/Majorana_Fermion_Operator_tutorial.ipynb) | Majorana fermion operators for fermionic simulation. |
| [Basis_rotated_Number_operator_(with_batching).ipynb](./tutorials/Basis_rotated_Number_operator_(with_batching).ipynb) | Basis-rotated number operators with batching. |
| [Antisymmetrization.ipynb](./tutorials/Antisymmetrization.ipynb) | Antisymmetrization for fermionic states. |

### Data loaders and QROM

| Notebook | Description |
| --- | --- |
| [Data_Loaders_QROM.ipynb](./tutorials/Data_Loaders_QROM.ipynb) | Quantum read-only memory (QROM) data loaders. |
| [SwapUp_Inject.ipynb](./tutorials/SwapUp_Inject.ipynb) | SwapUp injection technique. |
| [Compression_Gadget.ipynb](./tutorials/Compression_Gadget.ipynb) | Compression gadget for QROM-like loaders. |
| [Simple_Multiplexing_Examples.ipynb](./tutorials/Simple_Multiplexing_Examples.ipynb) | Basic multiplexing patterns. |

### Quantum arithmetic and Hamming weight

| Notebook | Description |
| --- | --- |
| [Vector_arithmetic.ipynb](./tutorials/Vector_arithmetic.ipynb) | Arithmetic on vector-valued quantum registers. |
| [Computing_the_Hamming_weight.ipynb](./tutorials/Computing_the_Hamming_weight.ipynb) | Computing the Hamming weight of a register. |
| [Hamming_weight_phasing.ipynb](./tutorials/Hamming_weight_phasing.ipynb) | Hamming-weight phasing for rotation synthesis. |
| [Batched_hamming_weight_phasing.ipynb](./tutorials/Batched_hamming_weight_phasing.ipynb) | Batched variant of Hamming-weight phasing. |
| [Bitonic_sort.ipynb](./tutorials/Bitonic_sort.ipynb) | Bitonic sort on a quantum register. |

## Feedback

Report issues at <https://github.com/PsiQ/psiqdk/issues/new/>.
