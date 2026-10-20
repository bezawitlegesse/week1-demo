# Week 1 Lab: Small Data-Processing App

A Python notebook that loads a raw CSV dataset, cleans it with functions, and analyzes it with NumPy.

## What it does
1. Loads messy data from a CSV (blanks, duplicates, bad numbers, out-of-range scores)
2. Cleans it with functions (`parse_score`, `clean_data`)
3. Processes it with NumPy (mean, median, std, percentiles, z-scores, letter grades)
4. Prints a ranked report

## How to run

### In Google Colab
1. Tap the "Open in Colab" badge at the top of `week1.ipynb`, or upload the file to colab.research.google.com.
2. Choose Runtime > Run all.
3. The notebook writes `requirements.txt`, creates a virtual environment (`.venv`), and installs the packages into it.

### Locally
1. Create a virtual environment: `python -m venv .venv`
2. Activate it: `source .venv/bin/activate` (Mac/Linux) or `.venv\Scripts\activate` (Windows)
3. Install the packages: `pip install -r requirements.txt`
4. Open `week1.ipynb` and run all cells.

## Files
- `week1.ipynb`: the notebook
- `requirements.txt`: dependencies (ipykernel, numpy, requests)
