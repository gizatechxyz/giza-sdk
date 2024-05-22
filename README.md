# giza-sdk

giza-sdk is a metapackage designed to simplify the installation and management of the Giza ecosystem of packages. It bundles three primary packages essential for Giza-related development.

Packages Included:

	
1.	[**giza-cli**](https://docs.gizatech.xyz/products/platform): A command-line interface for interacting with Giza services and tools.
2.  [**giza-agents**](https://docs.gizatech.xyz/products/ai-agents): Giza Agents is a framework for trust-minimized integration of machine learning into on-chain strategy and action.
3.	[**giza-datasets**](https://docs.gizatech.xyz/products/datasets):A package for managing and interacting with datasets in Giza.


## Installation

To install the giza-sdk and all included packages, run:

```bash
pipx install giza-sdk
```

## Usage

Now everything is available under the name giza! Here are some examples:

```python
from giza.datasets import DatasetsLoader
from giza import cli
from giza.agents import GizaAgent
```

## Uninstallation

To uninstall giza-sdk along with its dependencies, run:

```python
pip uninstall giza-sdk
```

## License

This project is licensed under the MIT License.