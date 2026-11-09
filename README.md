# greet-release

A small greeting program used to practice maintenance and releases.

## Install and run

```bash
uv sync
uv run --locked python greet.py Hee
uv run --locked pytest -q greet.py
```

Versioning: this project follows Semantic Versioning (MAJOR.MINOR.PATCH).
