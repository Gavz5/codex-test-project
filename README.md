# codex-test-project

A minimal Python "Hello, world!" package using a `src` layout.

## Getting started

Create and activate a virtual environment, then install dependencies (including dev extras for testing):

```bash
python -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install -e .[dev]
```

## Running the app

Execute the package module to print the greeting:

```bash
python -m hello_world
```

## Running tests

Run the test suite with `pytest`:

```bash
pytest
```
