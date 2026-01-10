# Documentation Index

This folder centralizes project notes, learning paths, and references to help you (and others) navigate and extend the notebooks efficiently.

## Objectives
- Build a strong foundation in core ML libraries (`numpy`, `pandas`, `matplotlib`).
- Practice practical data preprocessing workflows with reproducible steps.
- Maintain a tidy, professional repo that’s easy to run and extend.

## How to Navigate
- Library Basics: see the notebooks in [notebooks/ml_libraries](../notebooks/ml_libraries)
	- numpy_basics.ipynb — arrays, operations, broadcasting.
	- pandas_basics.ipynb — Series/DataFrame, selection, merge, groupby.
	- matplotlib_tutorial.ipynb — plotting essentials, styling.
- Data Preprocessing: see [notebooks/data_preprocessing](../notebooks/data_preprocessing)
	- reading_csv.ipynb — load and inspect tabular datasets.
	- train_test_split.ipynb — split with stratification and seed control.
	- handling_missing_values.ipynb — imputation strategies.
	- label_encoding.ipynb — encoding categorical features.
	- data_standardization.ipynb — scaling numeric features.
	- handling_imbalanced_dataset.ipynb — resampling/metrics for imbalance.
	- feature_extraction_of_text_data.ipynb — text vectorization.
	- numerical_dataset_pre_processing_usecase.ipynb — end-to-end example.

## Conventions
- Naming: use snake_case for files/folders (already applied under `notebooks/`).
- Reproducibility: set random seeds when applicable; prefer deterministic splits.
- Notebook outputs: consider clearing large outputs before committing to keep diffs clean.
- Paths: read data using relative paths from the repo root (e.g., `data/raw/...`).

## Environment
Prefer a virtual environment and install dependencies listed in [requirements.txt](../requirements.txt):

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

Launch Jupyter:

```bash
jupyter lab
# or
jupyter notebook
```

## Data Guidance
- Place datasets under [data](../data) (see its README for structure and policies).
- Avoid committing large/raw data; use small samples for examples.
- Consider Git LFS if you need to version large files.

## Roadmap
- Feature engineering patterns (polynomial features, target encoding, binning).
- Model training notebooks (classification, regression, evaluation).
- Pipeline patterns with `scikit-learn` (`ColumnTransformer`, `Pipeline`).
- Experiment tracking with lightweight tools (CSV logs, MLflow optional).

## References
- NumPy: https://numpy.org/doc/
- Pandas: https://pandas.pydata.org/docs/
- Matplotlib: https://matplotlib.org/stable/contents.html
- Scikit-learn: https://scikit-learn.org/stable/user_guide.html
