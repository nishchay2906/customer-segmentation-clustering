# Customer segmentation and classification

A coursework notebook that explores K-means and DBSCAN clustering, uses elbow and silhouette diagnostics, and compares supervised classifiers in later sections.

## Run the notebook

From the repository root, create and activate a Python virtual environment, then install the notebook dependencies.

```sh
python -m venv .venv
. .venv/bin/activate
python -m pip install jupyterlab pandas numpy matplotlib seaborn scikit-learn category-encoders lightgbm xgboost pycaret
python -m jupyterlab
```

Open [MMA_2022_869_Individual_Assignment.ipynb](MMA_2022_869_Individual_Assignment.ipynb) and select the virtual environment's Python kernel. Run the cells in order.

## Data

The notebook reads two CSVs from Google Drive URLs embedded near the start of the relevant sections. Both links must be accessible for a complete run.

The original assignment targeted Google Colab. The published notebook omits saved outputs that displayed row-level data. Current package combinations may need compatibility adjustments.
