# Project Template

My personal project template, for my Python/TS projects.

With this project template, you get:

- Automated testing on commit and when PRs are opened targeting the main branch
- `.env` validation via Pydantic Settings
- Devcontainer features, in particular:
  - Run tests and formatting on commit (via pre-commit)
  - Python linting with Ruff
  - Dockerfile linting with Hadolint
  - Non-root user setup
- Python package management with Poetry
- Pytest
- [`src/` project layout][src-layout]
- TODO run tests on commit
- TODO Code coverage
- TODO Dockerfile copy poetry venv
- TODO consider linting commit messages for automated release generation

To start using this template, click 'Use this template' on the top right.

If you found this template useful, feel free to contribute back!

[src-layout]: https://docs.pytest.org/en/7.1.x/explanation/goodpractices.html#src-layout
