# py-project-template
py-project-template

1. python3.12
2. pip24.2
3. pipx1.6.0
4. poetry1.8.3
5. pyenv ?? - skipped
6.  docker
7. taksfile3.38.0
8. ruff0.5.6
9. mypy1.11.1
10. pytest8.3.2
11. moto5.0.12
12. pydantic2.8.2
13. greatexpectations

## Docker installation

## Python installation

-

## Pip installation

`py -m ensurepip`

`mkdir C:/Users/<username>/pip`

`cp ./pip.ini C:/Users/<username>/pip`

# Pipx installation

`py -3.X -m pip install pipx==1.6.0`

`pipx ensurepath`

# Taskfile installation

`sh -c "$(curl --location https://taskfile.dev/install.sh)" -- -d -b C:/Dev/task`

add env path task/bin `C:/Dev/task/bin`

# Poetry installation

`pipx install poetry==1.8.3`

# Depencendcies installation

`poetry config virtualenvs.in-project true`

`poetry install`

`poetry add <packagename>==<package_version(optional)>`
`poetry remove <packagename>`