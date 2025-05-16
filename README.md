<h1 align="center">
  <img src="https://storage.googleapis.com/tbx-web-assets-2bad228/banners/tilebox-banner.svg" alt="Tilebox Logo">
  <br>
</h1>

<p align="center">
  <a href="https://docs.tilebox.com/introduction"><b>Documentation</b></a>
  |
  <a href="https://console.tilebox.com/"><b>Console</b></a>
  |
  <a href="https://tilebox.com/discord"><b>Discord</b></a>
</p>

# Tilebox Cassini Hackathon Starter Project

This repository contains starter notebooks for using the [Tilebox](https://tilebox.com) Python SDK.

More examples and documentation can be found [here](https://github.com/tilebox/examples) and in the [docs](https://docs.tilebox.com/).

## Prerequisites

- Python 3.10+
- Environment variables – provide your API key and cluster slug as environment variables via `.env` file
    - Tilebox API Key – [create here](https://console.tilebox.com/account/api-keys)
    - Tilebox Cluster slug – [create here](https://console.tilebox.com/workflows/clusters)
- Install the `uv` Python package manager – [installation instructions](https://docs.astral.sh/uv/)

## Getting Started

1. Clone the repository
2. Install dependencies with `uv sync`
3. Copy `.env.example` to `.env` and fill in the values
4. Run the notebooks in a Jupyter environment of your choice (e.g. `jupyterLab`, `vscode`, etc)

```python
# Run the notebook in JupyterLab
uv run --with jupyter jupyter lab .
```
