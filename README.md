# Numeric Methods

[![pre-commit.ci status](https://results.pre-commit.ci/badge/github/ChiefGokhlayeh/nm/main.svg)](https://results.pre-commit.ci/latest/github/ChiefGokhlayeh/nm/main)

Jupyter notebooks that form part of the Numeric Methods course at University of Esslingen.

## Setup

You'll need a IPython + NumPy environment to execute the included notebooks. If you don't already have one, feel free to use the provided `pyproject.toml` to obtain a local quick and dirty IPython installation, which can be used for example in combination with vscode.

## Google Colab

[![Open Notebooks In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ChiefGokhlayeh/nm)

The "Open in Cloab" badge will open a web-based Juypter-like IDE which pretty much contains all we need to execute the provided notebooks.

## Local Install

1. Install poetry as described [here](https://python-poetry.org/docs/#installation).
2. Clone this project using `git` or [download the ZIP](https://github.com/ChiefGokhlayeh/nm/archive/refs/heads/main.zip).

   ```sh
   git clone https://github.com/ChiefGokhlayeh/nm.git
   ```

3. Execute `poetry install --no-root` in the project root directory to download all dependencies into a project-local [virtual environment](https://docs.python.org/3/tutorial/venv.html).

4. Activate the newly installed virtual environment via `poetry shell`.

5. Install [Visual Studio Code](https://code.visualstudio.com/) + the [Jupyter](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter) extension to edit, or type `ipython <path-to-ipynb-file>` to execute a notebook top-to-bottom.
