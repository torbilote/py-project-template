# py-project-template
py-project-template

# core tools and dependencies
1. python==3.12
2. pip==24.2
3. pipx==1.7.1
4. docker==24.0.6
5. taskfile==3.38.0
6. ruff==0.6.2
7. mypy==1.11.1
8. pytest==8.3.2
9. pydantic==2.8.2
10. loguru==0.7.2

## Pip installation

`py -m ensurepip`

`mkdir C:/Users/<username>/pip`

`cp ./pip.ini C:/Users/<username>/pip`

`rm pip.ini`

# Pipx installation

`py -m pip install pipx==X.X.X`

`pipx ensurepath`

# Taskfile installation

`sh -c "$(curl --location https://taskfile.dev/install.sh)" -- -d -b "C:\\Users\\<username>\\.local\\bin" `

add env path task/bin `C:/Users/<username>/.local\\bin`

# Venv installation

`py -m venv .venv`

`. .venv/Scripts/Activate`

# Depencendcies installation

`py -m pip install -r requirements.txt`

`py -m pip install -r requirements-dev.txt`