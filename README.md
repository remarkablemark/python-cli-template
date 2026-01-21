# python-cli-template

[![PyPI version](https://img.shields.io/pypi/v/python-cli-template)](https://pypi.org/project/python-cli-template/)
[![codecov](https://codecov.io/gh/remarkablemark/python-cli-template/graph/badge.svg?token=l6pg0nf9aJ)](https://codecov.io/gh/remarkablemark/python-cli-template)
[![lint](https://github.com/remarkablemark/python-cli-template/actions/workflows/lint.yml/badge.svg)](https://github.com/remarkablemark/python-cli-template/actions/workflows/lint.yml)

🐍 Python CLI Template

## Quick Start

Greet a name:

```sh
pipx run python-cli-template --name world
```

## Prerequisites

- [Python](https://www.python.org/)
- [pipx](https://pipx.pypa.io/)

## CLI

Install the CLI:

```sh
pipx install python-cli-template
```

### `--name`

**Optional**: Name to greet. Defaults to `World`.

```sh
python-cli-template --name Alex
```

### `--version`

Show the program's version number and exit:

```sh
python-cli-template --version # python-cli-template -v
```

Show the help message and exit:

```sh
python-cli-template --help # python-cli-template -h
```

## Script

Create a virtual environment:

```sh
python3 -m venv .venv
```

Activate the virtual environment:

```sh
source .venv/bin/activate
```

Install the package:

```sh
pip install python-cli-template
```

Greet a name:

```py
# script.py
from python_cli_template import hello

print(hello("Bob"))
```

Run the script:

```sh
python script.py
```

## License

[MIT](https://github.com/remarkablemark/python-cli-template/blob/master/LICENSE)
