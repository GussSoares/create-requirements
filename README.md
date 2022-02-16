# create-requirements
A simple pre-commit hook to create a requirements.txt from pyproject.toml

## General Usage

Add the following code into the `.pre-commit-config.yaml` file:

```yaml
-   repo: https://github.com/GussSoares/create-requirements
    rev: 'v0.1.0'
    hooks:
      - id: create-requirements

```
