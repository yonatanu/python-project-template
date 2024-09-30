# Python Project Template

This is a basic Python project structure for quick setup.

## Project structure

- `src/`: Main project source code.
- `tests/`: Unit tests.
- `pyproject.toml`: Project configuration and dependency management.
- `env.yaml`: Python environment setup for `conda` or `pip`.

## How to use

1. Clone this repo: `git clone <url>`
2. Set up the environment:
   - Using `conda`: `conda env create -f env.yaml`
   - Using `pip`: `pip install -r requirements.txt`
3. Run tests: `pytest`
4. Remember to update the project name in `pyproject.toml` and the folder name `src/project` accordingly.
5. To install the current package in debug mode run: `pip install -e .`
6. To install pre-commit run `pre-commit install`