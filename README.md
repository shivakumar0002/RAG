# RAG

A Python project for building a Retrieval-Augmented Generation (RAG) application.

## Requirements

- Python 3.12 or newer
- [`uv`](https://docs.astral.sh/uv/)

## Setup

Create a virtual environment named `rag`:

```bash
uv venv rag
```

Activate it on macOS or Linux:

```bash
source rag/bin/activate
```

Tell `uv` to use `rag` as this project's environment instead of its default
`.venv` directory:

```bash
export UV_PROJECT_ENVIRONMENT=rag
```

Install and synchronize the project dependencies:

```bash
uv sync
```

## Run the application

```bash
uv run main.py
```

The starter application prints:

```text
Hello from rag!
```

## Add dependencies

Use `uv add` so dependencies are recorded in `pyproject.toml` and locked in
`uv.lock`:

```bash
uv add <package-name>
```

For example:

```bash
uv add langchain
```

## Deactivate the environment

```bash
deactivate
```

When opening a new terminal, activate the environment and set
`UV_PROJECT_ENVIRONMENT` again before running project commands:

```bash
source rag/bin/activate
export UV_PROJECT_ENVIRONMENT=rag
```
