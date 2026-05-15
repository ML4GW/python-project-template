# Installation

## From PyPI

```bash
pip install my-package
```

Or with [uv](https://docs.astral.sh/uv/):

```bash
uv pip install my-package
```

## Development Install

Clone the repository and install with development dependencies:

```bash
git clone https://github.com/ML4GW/my-package
cd my-package
uv sync --group dev
```

Install pre-commit hooks:

```bash
uv run prek install
```
