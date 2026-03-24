# Breast Cancer Classification (Logistic Regression)

A comprehensive machine learning project focusing on the classification of breast cancer tumors as **Malignant** or **Benign** using Logistic Regression. This project demonstrates high-performance predictive modeling and advanced hyperparameter optimization techniques.

## Overview
Accurate medical diagnosis is a critical application of machine learning. This repository provides a complete analytical pipeline, from exploratory data analysis (EDA) to model deployment preparation, utilizing the Wisconsin Breast Cancer Diagnostic dataset.

### Key Features
- **Exploratory Data Analysis**: Visualizing class distributions and feature statistics.
- **Predictive Modeling**: Robust implementation of a Logistic Regression classifier using `scikit-learn`.
- **Optimization**: Hyperparameter tuning via `GridSearchCV` (C, solver, penalty) with 5-fold cross-validation.
- **Performance Evaluation**: Comprehensive metrics including Confusion Matrix, Precision, Recall, and F1-Score.

## Project Structure
```text
breast-cancer-logistic-regression/
│
├── data/                 # Raw and augmented datasets
├── notebooks/            # Jupyter Notebooks for research and development
│
├── .gitignore            # Git exclusion rules
├── README.md             # Project documentation (current)
└── requirements.txt      # List of required Python packages
```

## Installation

### Prerequisites
- Python 3.9 or higher
- `pip` or `conda` environment manager

### Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/breast-cancer-logistic-regression.git
   cd breast-cancer-logistic-regression
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
The core logic and experiments are documented in the Jupyter notebook located in the `notebooks/` directory.

```bash
jupyter notebook notebooks/Logistic_Regression_Breast_Cancer.ipynb
```

## Model Performance
The current baseline model highlights excellent predictive capabilities:
- **Baseline Accuracy**: ~98.25%
- **Hyperparameter Optimized**: Achieved ~98.02% (Cross-Validation Score)

Detailed evaluation reports and confusion matrices are generated within the notebook to visualize model behavior and error patterns.

## Dataset Source
This project uses the **Breast Cancer Wisconsin (Diagnostic)** dataset from the `sklearn.datasets` module.
- **Total Samples**: 569
- **Features**: 30 numeric attributes (radius, texture, perimeter, area, etc.)
- **Target Classes**: 212 Malignant (0), 357 Benign (1)

---
*Developed for academic purposes in the Introduction to Machine Learning Course (2026).*
