# Contributing Guide

Thanks for considering a contribution! This is a personal portfolio/project repo — PRs are welcome but not expected.

## How to Contribute

1. **Fork** the repo
2. **Create a branch**: `git checkout -b feat/your-change`
3. **Make changes** — keep commits atomic
4. **Run lint/tests** locally before pushing
5. **Open a PR** with a clear description

## Code Style

- **Python**: `ruff` for lint + format (replaces flake8, black, isort)
- **Node/TypeScript**: `oxlint` + `prettier` (or project-specific)
- **Commits**: Conventional commits (`feat:`, `fix:`, `docs:`, `refactor:`)

## Local Setup

```bash
# Python
pip install -r requirements.txt
pip install ruff pytest

# Node
npm ci
```

## Testing

```bash
# Python
pytest -v

# Node
npm run test  # if available
```

## Reporting Issues

- Use issue templates if available
- Include reproduction steps
- Specify environment (OS, Python/Node version)