# Algorithms

**Algorithms** is a library of reusable quantum-algorithm primitives and subroutines built on top of [Workbench](../workbench). It provides production-quality implementations of the building blocks that appear in almost every fault-tolerant quantum algorithm - state preparation, amplitude amplification, phase estimation, QROM-based data loading, quantum arithmetic, and more - each accompanied by symbolic resource estimates.

This folder contains the **tutorial notebooks** for the Algorithms library.

## Documentation

[Full Algorithms documentation](https://construct.psiquantum.com/docs/workbench_algorithms/index.html).

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

The [`tutorials/`](./tutorials) directory contains runnable Jupyter notebooks (the notebooks used to generate the documentation pages).

## Getting help

Please [file an issue](https://github.com/PsiQ/psiqdk/issues/new/) to report a bug or to request a feature, or [start a discussion](https://github.com/PsiQ/psiqdk/discussions/new/choose) to ask a question.
