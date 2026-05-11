# PsiQuantum Development Kit (PsiQDK)

Welcome to the **PsiQuantum Development Kit** - an integrated set of Python packages for designing, simulating, and analyzing quantum programs targeted at PsiQuantum's fault-tolerant photonic quantum computer.

PsiQDK bundles the core components you need to write a quantum program, simulate it, estimate its cost on fault-tolerant hardware, and visualize the results - all under a single, version-aligned distribution.

## What's in PsiQDK?

| Component | Purpose |
| --- | --- |
| **[Workbench](./workbench)** | A Python framework with an optimized C++ backend for writing and simulating quantum programs, plus symbolic resource estimation. |
| **[Algorithms](./algorithms)** | A growing library of reusable quantum algorithm primitives - state preparation, arithmetic, phase estimation, QROM, and more. |
| **[Visualize](./visualize)** | Jupyter widgets and editor integrations for inspecting circuits and resource-estimation reports. |
| **[End-to-end examples](./e2e)** | Full workflows that combine circuit design, implementation, simulation, and resource estimation on real algorithms. |

## Installation

### Prerequisites

- **Python**: 3.11, 3.12, or 3.13
- **Operating system**: Linux or macOS (Windows via WSL)
- **Optional**: [GraphViz](https://graphviz.org/) for rendering call graphs in resource-estimation reports

### Installing PsiQDK

PsiQDK is distributed as a single meta-package that pins compatible versions of each component:

```bash
pip install psiqdk
```

Once installed, verify the installation:

```bash
psiqdk --version
psiqdk --verify
```

## Documentation and examples

- **Official documentation**: <https://open-docs.construct.psiquantum.com/>
- **Tutorials in this repository** - Jupyter notebooks that mirror the documentation and can be run end-to-end:
  - [Workbench tutorials](./workbench/tutorials) - gates, qubit management, simulation, resource estimation, and the Qubricks framework.
  - [Algorithms tutorials](./algorithms/tutorials) - state preparation, amplitude amplification, phase estimation, arithmetic, QROM, and more.
  - [Visualization examples](./visualize) - interactive circuit and QRE viewers for Jupyter and VS Code.
  - [End-to-end examples](./e2e/tutorials) - full algorithm-design → implementation → resource-estimation workflows (Grover SAT solver, recursive state preparation).

## Other learning resources

- **[Workbench Quantum Katas](https://github.com/PsiQ/workbench-quantum-katas)** - a hands-on collection of tutorials and programming exercises that teach quantum computing and quantum programming, from basic concepts to fault-tolerant applications such as quantum chemistry.
- **[Quantum Programming in Depth](https://github.com/tcNickolas/quantum-programming-in-depth)** - side-by-side code samples in three quantum development toolkits: Workbench, Q#, and Qiskit.

## Support policy

PsiQuantum officially supports the **current Stable** release of PsiQDK. Older releases are best-effort only.

## Feedback and contributing

We welcome bug reports, feature requests, and discussion. Please file a [new issue](https://github.com/PsiQ/psiqdk/issues/new/) on this repository.

## License

See [LICENSE](./LICENSE).

© PsiQuantum Corp.
