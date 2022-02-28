# {{ cookiecutter.project_name }}

{{ cookiecutter.project_short_description }}

### Development
In this repo we use a few tools to keep the code clean, styled and properly tested:
```shell
make lint  # runs flake8 and Black check
make autoformat  # runs Black formating
make typecheck  # runs mypy
make test  # runs unit [py]tests
```

This package was created with Cookiecutter and the [matejker](https://github.com/matejker)/[cookiecutter-poetry](https://github.com/matejker/cookiecutter-poetry) project template.