# Python Workspace

#### A quick-start template for Python projects.

### Prerequisites

- [Py Launcher](https://python-launcher.app/install/)
- [Pip Compile](https://pip-tools.readthedocs.io/en/stable/)

### Project Setup

1. Create a virtual env with desired version of Python
   1. Example, with `py-launcher`
   2. `py -3.11 -m venv .venv`
2. Install dependencies
   1. `py -m pip install -r requirements.txt`

### Adding Dependencies

1. Use `pip-compile` to generate a new `requirements.txt`
   1. `py -m pip install pip-tools`
   2. Add dependency to `requirements.in`
   3. Run `pip-compile requirements.in`
