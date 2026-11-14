# Template-mkdocs

## Usage

### Local

Install [uv](https://docs.astral.sh/uv/getting-started/installation/), then run:

```bash
git clone git@github.com:ymmmtym/template-mkdocs.git
cd template-mkdocs
uv python install
uv sync
```

build

```bash
uv run mkdocs build
```

run

```bash
uv run mkdocs serve -a 0.0.0.0:8000
```

### GitHub Pages

1. Push or Merge to main branch.
2. GitHub Pages will be deployed at gh-pages branch.
