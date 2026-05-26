# Visualize

Interactive viewers for **quantum circuits** and **quantum resource estimation (QRE) reports** produced by [Workbench](../workbench) and [Algorithms](../algorithms). The same visualization that powers the Construct app is available as a Jupyter widget and a VS Code extension, so you can inspect circuits and QREs wherever you work.

## Documentation

[Full PsiQDK documentation](https://open-docs.construct.psiquantum.com/).

## What's included

| Surface | Description |
| --- | --- |
| **Jupyter widget** | An [`anywidget`](https://anywidget.dev/)-based widget that embeds the Construct viewer directly inside notebooks. View circuits, call graphs, and flame graphs inline. |
| **VS Code extension** | Open `.circuit` and `.qre-analysis` files directly in VS Code with the same interactive viewer. |

## Installation

The Jupyter widget is bundled with [PsiQDK](../README.md):

```bash
pip install psiqdk
```

The VS Code extension is distributed as a `.vsix` package and can be installed via the VS Code Marketplace or the published artifact.

## Usage - Jupyter widget

```python
from psiqdk.visualize import CallGraph, FlameGraph, Circuit

# Render a QRE analysis as an interactive call graph.
CallGraph(src="myprogram.qre-analysis")

# Show a specific flame-graph view of the same QRE.
FlameGraph(src="myprogram.qre-analysis", graph="toffs")

# Render a circuit design from a file or URL.
Circuit(src="myprogram.circuit")
```

The widgets accept either a local file path or an `https://` URL pointing to a circuit or QRE artifact.

## Getting help

Please [file an issue](https://github.com/PsiQ/psiqdk/issues/new/) to report a bug or to request a feature, or [start a discussion](https://github.com/PsiQ/psiqdk/discussions/new/choose) to ask a question.
