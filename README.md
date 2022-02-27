# A template repo for Python projects

To use this template, click the green button at the top of the GitHib page that's cleverly called **"Use this template"**.

This template currently uses Python 3.10. It also includes:

- [pip-tool](https://pypi.org/project/pip-tools/) for dependency management.
- [pytest](https://docs.pytest.org/en/6.2.x/) for testing
- [pre-commit](https://pre-commit.com/) hooks for:
  - [isort](https://pycqa.github.io/isort/)
  - [black](https://black.readthedocs.io/en/stable/)
  - [flake8](https://flake8.pycqa.org/en/latest/)
- GitHub Actions for continuous integration.
- [Flit](https://flit.readthedocs.io/en/latest/index.html) for building distribution files.

## Setup

To create a virtual environment and install all dependencies, run:

```shell
# On windows
> python -m venv .venv
> .venv/Scripts/Activate
> python -m pip install --upgrade pip
> python -m pip install -r requirements.txt 
```

Now initialize the pre-commit hooks:

```shell
> pre-commit install
```

That's it, you're all set to start coding your application!
