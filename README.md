# Rare Disease Genes — Data Analysis

## About This Project
I analyzed a dataset of around 8000 rare diseases and 5000 genes
to explore [what question interested you most?].

## What I Found
- How to plot graphs properly and simply
- The lack of diseases that include the tumor
- Different diseases in certain age groups

## Tools Used
- Python
- pandas — for loading and filtering data
- matplotlib — for creating charts

## Installation

**Prerequisites:** [Python](https://www.python.org/downloads/) **3.9+** (required for pandas 2.x).

From the project root, create a virtual environment, activate it, and install dependencies:

**macOS / Linux**

```bash
python3 -m venv .venv
source .venv/bin/activate
python -m pip install --upgrade pip
pip install -r requirements.txt
```

**Windows (Command Prompt or PowerShell)**

```bash
python -m venv .venv
.venv\Scripts\activate
python -m pip install --upgrade pip
pip install -r requirements.txt
```

The `.venv` folder is listed in `.gitignore` and stays on your machine only.

To leave the virtual environment later, run `deactivate`.

**Running the notebooks:** In VS Code or Cursor, open a `.ipynb` file and choose the Python interpreter that points to `.venv/bin/python` (macOS/Linux) or `.venv\Scripts\python.exe` (Windows). The `ipykernel` package in `requirements.txt` lets the editor attach the notebook to that environment.

## Files
- `notebooks/HW1.ipynb` — main analysis notebook
- `results/findings.md` — written summary of findings

## Data Source
Data from [Orphadata](https://www.orphadata.com/) and [Ensembl](https://www.ensembl.org/).