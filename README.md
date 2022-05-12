# Python cookiecutter Machine Learning template

This is a [cookiecutter](https://github.com/cookiecutter/cookiecutter) template
for my machine learning projects. This is a modified version of the
[data science cookiecutter](https://drivendata.github.io/cookiecutter-data-science/)
template, with less files and the addition of
[poetry](https://python-poetry.org/)

## Usage

Make sure `cookiecutter` is installed

```terminal
pip install cookiecutter
```

Then run cookiecutter with this template:

```terminal
cookiecutter https://github.com/thesofakillers/mlcookiecutter
```

After initializing, remember to:

1. create the appropriately versioned python environment, if you wish to use
   environments
2. `cd` to the generated directory
3. Run `git init` to initialize version control
   1. setup a remote address optionally
4. optionally add a LICENSE file, updating `pyproject.toml` file accordingly
5. run `poetry update` to generate a `poetry.lock` file.
6. commit the contents of the directory.
