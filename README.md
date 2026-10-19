# greet-ci

Greeting CLI program and CI workflow using uv.

## Installation

```bash
uv sync
```

## Running

```bash
uv run python greet.py Hee
uv run python greet.py
```

## Tests and Quality Checks

```bash
uv run pytest -q greet.py
uv run black --check greet.py
uv run flake8 greet.py
uv run mypy greet.py
```

## Build

```bash
uv build
```
