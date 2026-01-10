# Machine Learning Notebooks

A curated set of Jupyter notebooks documenting my machine learning learning journey — from core Python/ML libraries to practical data preprocessing workflows.

## Overview
- Learn the essentials of `numpy`, `pandas`, and `matplotlib`.
- Practice end-to-end preprocessing: handling missing values, encoding labels, train/test split, class imbalance, and more.
- Keep things organized and reproducible with a clean project structure.

## Repository Structure
```
.
├── notebooks/
│   ├── ml_libraries/
│   │   ├── matplotlib_tutorial.ipynb
│   │   ├── numpy_basics.ipynb
│   │   └── pandas_basics.ipynb
│   └── data_preprocessing/
│       ├── data_standardization.ipynb
│       ├── feature_extraction_of_text_data.ipynb
│       ├── handling_imbalanced_dataset.ipynb
│       ├── handling_missing_values.ipynb
│       ├── label_encoding.ipynb
│       ├── numerical_dataset_pre_processing_usecase.ipynb
│       ├── reading_csv.ipynb
│       └── train_test_split.ipynb
├── data/
│   └── README.md
├── docs/
│   └── README.md
├── .gitignore
└── requirements.txt
```

## Setup
1. Ensure Python 3.9+ is installed.
2. Create and activate a virtual environment.

```bash
# macOS
python3 -m venv .venv
source .venv/bin/activate

# Install dependencies
pip install -r requirements.txt
```

## Usage
Launch Jupyter and start exploring the notebooks:

```bash
jupyter notebook
# or
jupyter lab
```

Open notebooks under `notebooks/ml_libraries` to review library basics, then continue with `notebooks/data_preprocessing` for practical workflows.

## Notes
- The `data/` folder is a placeholder; datasets are not committed. Use `data/raw/` and `data/processed/` subfolders as your workflow evolves.
- If you work with large files, consider using Git LFS.

## Next Steps
- Add more preprocessing and feature engineering examples.
- Introduce model training notebooks (classification, regression, evaluation).