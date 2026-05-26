# Workbench

**Workbench** is a Python package designed for efficient writing and execution of quantum programs. It allows developers to create quantum circuits and algorithms using Python, while leveraging the performance of an optimized, multi-threaded C++ core.

This folder contains the **tutorial notebooks** that accompany the official Workbench documentation.

## Features

- **FTQC Primitives**: Build with abstractions designed for fault-tolerant quantum computing, including quantum data types, mid-circuit measurements, and automatic uncompute.

- **Built for Runtime**: Scale to large circuits and runtime-style execution with support for streaming billions of operations without relying on fixed kernels.

- **Large Algorithm Library**: Access more than 100 interoperable, FTQC-focused algorithm implementations, including alias sampling, quantum phase estimation, and more.

- **Quantum Resource Estimates (QREs)**: Generate accurate QREs for circuits of any size, including circuits with billions of gates, and analyze results with Resource Analyzer, Bartiq, or the Resource Estimator.

- **Hardware Agnostic**: Write, compile, and optimize quantum algorithms for a range of FTQC hardware architectures. 

- **Highly Performant Simulation**: Iterate quickly with optimized C++ simulation, including native bit and Clifford simulators as well as GPU-powered tensor-network and state-vector simulation via CUDA-Q.

## Documentation

[Full Workbench documentation](https://open-docs.construct.psiquantum.com/psiq_workbench/index.html).

## Installation

Workbench ships as part of [PsiQDK](../README.md):

```bash
pip install psiqdk
```

Workbench is then available under the `psiqdk.workbench` namespace:

```python
from psiqdk.workbench import ...
```

## Tutorials

The [`tutorials/`](./tutorials) directory contains runnable Jupyter notebooks (the notebooks used to generate the documentation pages).

## Getting help

Please [file an issue](https://github.com/PsiQ/psiqdk/issues/new/) to report a bug or to request a feature, or [start a discussion](https://github.com/PsiQ/psiqdk/discussions/new/choose) to ask a question.
