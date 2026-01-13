# Dirigo Documentation

This repository contains the source files for the Dirigo documentation,
published at:

https://dirigo.readthedocs.io

The main Dirigo source code lives here:
https://github.com/dirigo-developers/dirigo

## Building locally

To build the documentation locally, create a virtual environment and install the
documentation dependencies:

```bash
pip install -r requirements.txt
```

Then build the HTML documentation:
```
cd docs
python -m sphinx -b html . _build/html
start _build/html/index.html
```

## Read the Docs
Read the Docs is configured to build this repository directly using
`.readthedocs.yaml`.

