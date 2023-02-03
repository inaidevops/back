# Ebilim 2.0

## How to run in debug mode

At first, you need the [**Poetry**](https://python-poetry.org/) package manager for python

### Linux, Macos, WSL

```sh
curl -sSL https://install.python-poetry.org | python3 -
```

### Windows (Powershell)

```sh
(Invoke-WebRequest -Uri https://install.python-poetry.org -UseBasicParsing).Content | py -
```

> Note: If you have installed Python through the Microsoft Store, replace py with python in the command above.

### Add Poetry to your PATH

The installer creates a poetry wrapper in a well-known, platform-specific directory:

`$HOME/.local/bin` on Unix.

`%APPDATA%\Python\Scripts` on Windows.

`$POETRY_HOME/bin` if `$POETRY_HOME` is set.

If this directory is not present in your `$PATH`, you can add it in order to invoke Poetry as poetry.

Alternatively, the full path to the poetry binary can always be used:

`~/Library/Application Support/pypoetry/venv/bin/poetry` on MacOS.

`~/.local/share/pypoetry/venv/bin/poetry` on Linux/Unix.

`%APPDATA%\pypoetry\venv\Scripts\poetry` on Windows.

`$POETRY_HOME/venv/bin/poetry` if `$POETRY_HOME` is set.

## Install Dependencies and Start VirtualEnv

To install project dependencies just type in your project terminal

```sh
poetry install
```

To start virtualenv

```
poetry shell
```

To exit virtualenv

```
exit
```
