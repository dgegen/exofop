# Installation

## Using pip

The recommended method of installing __ExoFOP__ is with [`pip`](https://pip.pypa.io):

```bash
pip install exofop
```

## From Source

To install the package from source run
```bash
git clone https://github.com/dgegen/exofop.git
cd exofop
python3 -m pip install
```
or install in editable mode
```bash
python3 -m pip install -e .
```
For more information, consult the
[Python Packaging User Guide](https://packaging.python.org/en/latest/tutorials/installing-packages/#installing-from-a-local-src-tree).

### Optional Dependencies

The package supports additional features through optional dependencies.
You can install these dependencies based on your needs. Choose from the following options:

```bash
# To also install visualization tools, including matplotlib and notebook
python3 -m pip install ".[visualization]"
```

### Contributing and Testing

To run the unit tests, install the development dependencies and run pytest with [uv](https://docs.astral.sh/uv/):

```bash
uv sync --dev
uv run pytest
```
