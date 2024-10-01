# Software Engineers optimization by Issue priority

## Link
[Collab Development](https://github.com/JuanCruzCaggiano/Simulacion-TP6/blob/main/notebooks/simulation.ipynb)

## Setting Up environment

### Option A - Using poetry

Install poetry globally:

```bash
pip install poetry
```

Install dependencies, `poetry` will create a virtual environment for you:

```bash
poetry install
```

For using the virtual environment in `Jupyter Notebook` create a kernel:

```bash
poetry run python -m ipykernel install --user --name tp6
```

> NOTE: you can change `tp6` to any other name you want.

### Option B - Using pip

Install dependencies:

```bash
pip install -r requirements.txt
```

For using the virtual environment in `Jupyter Notebook` create a kernel:

```bash
python -m ipykernel install --user --name tp6
```
