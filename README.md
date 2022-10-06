# Introduction To Python workshop at UCSAS 2022

## Get the materials

All located in the root of this repository.

## Running locally

### Setting up the Jupyter Notebook

#### Regular Pip

In the current directory

```bash
python3 -m venv env
source env/bin/activate # Change for your shell if needed
pip install -r requiremnts.txt
jupyter notebook
```

#### Poetry

```bash
poetry lock
poetry shell
jupyter notebook
```

### Making the Slides

1. Install Marp with npm (node v16 or greater)

```shell
npm i -g @marp-team/marp-cli
```

2. Run the converter to PDF/PPTX/HTML:

PPTX:

```bash
marp --theme assets/gradient.css . --pptx --allow-local-files
```

PDF:

```bash
marp --theme assets/gradient.css . --pdf --allow-local-files
```

HTML

```
marp --theme assets/gradient.css . --html --allow-local-files
```
