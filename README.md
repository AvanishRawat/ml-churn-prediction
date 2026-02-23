# ML Churn Prediction

A lightweight machine-learning project that explores customer churn prediction on the Telco Churn dataset using two Jupyter notebooks:

- `notebooks/01_eda.ipynb`: exploratory analysis and churn signal discovery.
- `notebooks/02_preprocessing_and_baselines.ipynb`: preprocessing, logistic regression baseline, random forest baseline, and threshold tuning.

## Repository structure

- `notebooks/`: analysis and modeling workflow.
- `src/utils/`: utility package placeholder for reusable Python helpers.
- `requirements.txt`: Python dependencies used by the notebooks.

## Setup

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

## Data

The notebooks expect the dataset at:

```text
data/raw/telco_churn.csv
```

Place the CSV there before running notebook cells.

## Quick quality checks used in this repo

- Validate notebook JSON and Python syntax extracted from code cells.
- Verify imports required by notebook code are represented in `requirements.txt`.

## Notes

This project is notebook-first. If you intend to productionize models, consider moving preprocessing and training logic into modules under `src/` and adding automated tests.
