# Template repository for Papers

Repository using [Cookiecutter](https://cookiecutter.readthedocs.io/en/stable/README.html) for project templates.

## Installation
To use this repository, you need to install cookiecutter. This can be done with `pip`
```bash
python3 -m pip install cookiecutter
```
For other installation options, see: [Cookiecutter installation](https://cookiecutter.readthedocs.io/en/stable/installation.html)

You also need to have `git` installed on your system, see:
[Download git](https://git-scm.com/downloads) for more information.

## Usage
To use this repository with cookiecutter you can call:
```bash
cookiecutter gh:scientificcomputing/generate-paper
```
and fill out the list of options.

# Options for cookiecutter
The following options are available when using the cookiecutter:

1. __Full Name__: Will appear in the `pyproject.toml` file as the author. Will also be used as author of the documentation generated by [jupyter-book](https://scientificcomputing.github.io/reproducibility/part3/publishing.html).
2. __Email__: Will be used in `pyproject.toml` for package information.
3. __github\_username__: Will be used to fetch the correct links for the documentation and [license badge](https://scientificcomputing.github.io/reproducibility/part5/badges.html#licence).
4. __project\_name__: Used in various headers of the documentation
5. __repository\_name__: Name of the repository
6. __version__: The initial version of the software.
7. __open\_source\_license__: Choose a open source license for your code
8. __use_pre_commit__: Set up [pre-commit hooks](https://pre-commit.com) that will run some checks
9. __require_fenics__: Does your paper require FEniCS?
10. __require_fenicsx__: Does your paper require FEniCSx?