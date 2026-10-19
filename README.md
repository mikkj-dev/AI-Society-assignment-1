# AI & Society – Assignment 1 (CSET485)

**Student:** S24CSEU2599

Income-prediction analysis on the Adult (Census Income) dataset, with a fairness audit of the models.

## Contents

| Path | Description |
|------|-------------|
| `notebook/` | Executed Jupyter notebook `CSET485_Assignment1_S24CSEU2599.ipynb` (with outputs) |
| `adult.csv/` | Adult/Census Income dataset |

## What the notebook covers

1. **Data preparation**: missing values, categorical grouping, one-hot encoding, IQR outlier review, `log1p` transform for skewed capital gain/loss
2. **Modelling**: OLS vs logistic regression, with threshold comparison
3. **Simpson's paradox**: search for subgroup trends that reverse in aggregate
4. **Omitted-variable bias**: demonstration of how a missing variable distorts coefficients
5. **Adversarial subset experiment**
6. **Fairness sweep**: demographic parity (DP), equalized odds (EO) and predictive parity (PP)
7. **Written answers** for Parts 3 and 4

## How to run

```bash
pip install pandas numpy scikit-learn statsmodels matplotlib jupyter
jupyter notebook
```

Open the notebook in `notebook/` and run all cells. Make sure the dataset path in the loading cell points to the `adult.csv` file in this repo.

## Notes

- The notebook is committed with its outputs, so tables and figures render directly on GitHub.
- This repository is private and submitted for coursework.
