# ThreFhold
This repository contains a Jupyter Notebook file that demonstrates the ThreFhold methodology.

## What is ThreFhold
ThreFhold is a heuristic for determining the number of features to use for classification.

### Highlights
- data-driven
- one-shot estimate with no recursive mechanism
- reduced parameter selection
- interpretable mechanism

### How it was Made
ThreFhold was made by creating a machine learning model that estimates the proportion of features in synthetic datasets that were informative for classification.

## Get Started
> [!IMPORTANT]
> [uv](https://docs.astral.sh/uv/) is required to run the notebook. See the installation guide [here](https://docs.astral.sh/uv/getting-started/installation/).

### Sync Environment
Run the command below to create the virtual environment needed for running the Jupyter Notebook file.

```
uv sync
```

### Activating Jupyter Notebook
Once you have the virtual environment, run the command below to activate an environment with the right libraries for running the Jupyter Notebook file.

```
uv run jupyter notebook
```