# Week 1 Lab: Small Data-Processing App

A Python notebook that loads a raw CSV dataset, cleans it with functions, and analyzes it with NumPy.

## What it does
1. Loads messy data from a CSV (blanks, duplicates, bad numbers, out-of-range scores)
2. Cleans it with functions (`parse_score`, `clean_data`)
3. Processes it with NumPy (mean, median, std, percentiles, z-scores, letter grades)
4. Prints a ranked report

## How to run
**Colab:** upload `week1.ipynb` to colab.research.google.com and choose Runtime > Run all.

**Locally:**
python -m venv .venv
pip install -r requirements.txt
Open week1.ipynb and run all cells.

## Files
- `week1.ipynb`: the notebook
- `requirements.txt`: dependencies (numpy, ipykernel)
