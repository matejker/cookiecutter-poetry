# Poetry python package cookiecutter
> a classic copypasta before developing any (Python) project

A boilerplate for Python packages using Poetry and other conventions.

## Usage
1. Install `cookiecutter` using e.g.:
```bash
brew install cookiecutter
```
_Other ways to install `cookiecutter`, see [docs](https://cookiecutter.readthedocs.io/en/1.7.2/installation.html)._

2. Run `cookiecutter` in parent directory where your project will be located:
```bash
cookiecutter https://github.com/matejker/cookiecutter-poetry.git  # for HTTP
cookiecutter git+ssh://git@github.com:matejker/cookiecutter-poetry.git  # for SSH
```
3. Follow `cookiecutter's` command line dialog and set project name, description etc...
4. (Optional but essential) Set up git yourself using:
```bash
git init
```
