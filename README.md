# giza-sdk

giza-sdk is a metapackage designed to simplify the installation and management of the Giza ecosystem of packages. It bundles three primary packages essential for Giza-related development.

Packages Included:

	
1.	**giza-cli**
	•	Description: A command-line interface for interacting with Giza services and tools.
	•	Usage: Facilitates various operations like project setup, deployment, and management within the Giza ecosystem.
2.	**giza-agents**
	•	Description: A software development kit for building and managing Giza actions.
	•	Usage: Provides libraries and tools to create, test, and deploy actions in the Giza environment.
3.	**giza-datasets**:
- **Description**: A package for managing and interacting with datasets in Giza.
	•	Usage: Offers utilities for importing, exporting, and processing datasets used in Giza projects.

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
from giza.agents.agent import GizaAgent
```

## Uninstallation

To uninstall giza-sdk along with its dependencies, run:

```python
pip uninstall giza-sdk
```

## License

This project is licensed under the MIT License.