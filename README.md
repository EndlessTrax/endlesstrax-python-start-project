# A template repo for Python projects

To use this template, click the green button at the top of the GitHib page that's cleverly called **"Use this template"**.

This template currently uses Python 3.13. But test run on 3.9 and above. It also includes:

- [ruff](https://github.com/astral-sh/ruff) for linting and formatting.
- [pytest](https://docs.pytest.org/en/6.2.x/) for testing
- GitHub Actions for continuous integration and deployment.

## Setup

To create a virtual environment and install all dependencies, run:

```shell
$ uv venv

$ uv sync --all-extras --dev
```

That's it; you're all set to start coding your application!

## Build and Release

Use `uv build` to build a distribution file locally.

To release a new version, tag the commit with `v*.*.*` and push to the remote. The Github action will automatically build and upload the distribution file. Be sure to set a `PYPI_API_TOKEN` environment variable with your PyPI API token to upload to PyPi before tagging a release version.
