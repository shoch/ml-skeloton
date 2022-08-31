# ml-skeloton


# Usage

# Contribution
## Pre-commit hooks
This project provides pre-commit hooks for developers. Run 'pre-commit install' to setup git hook scripts. In case you actively want to ignore all hooks, use git commit --no-verify.

## Testing

cd <project>
pytest -m "not integtest"
pytest -m integtest
pytest -m "not slow"
pytest don't can handle marks on fixtures
