# Documentation

For more information about `pyproject.toml` and how it may be written check the reference.
---
`Poetry.lock` left for testing or viewing purposes.

## Useful commands

#### Running inside poetry's env
```bash
# If you declared the libraries in the pyproject.toml file, you may install them with this command.
poetry install

# to tuna file within the pyproject.toml
poetry run <script>
```
#### Configure poetry's env with requirements.txt
```bash

# if you wish to include the venv inside the project remember to execute
poetry config virtualenvs.in-project true

## import requirements.txt (project libraries) inside poetry
poetry add $( cat requirements.txt )
```

### Reference

- [Python Biella Group](https://pythonbiellagroup.it/en/gestire-dipendenze/poetry-advance/)