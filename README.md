# Project Template

My personal project template, for my Python/TS projects.

Features:

- Automated testing (via Dockerfile `test` stage) with coverage report via GHA
- Linting with Ruff
- Secret scanning
- Dockerfile with non-root user
- [`src/` project layout][src-layout]

## Getting Started

You will need to have `uv` installed.

To start using this template, click 'Use this template' on the top right.

Create a root `env/` folder, and add `local.env` and `prod.env` inside for your local and production environment variables respectively.

Run `uv sync`.

Run your project with `python -m my_project.main`.

If you found this template useful, feel free to contribute back!

## Useful Info

Skip pre-commit hooks:

`git commit --no-verify -m 'my commit'`

[src-layout]: https://docs.pytest.org/en/7.1.x/explanation/goodpractices.html#src-layout
