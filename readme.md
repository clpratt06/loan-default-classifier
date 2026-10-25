# Loan Default Risk Modeling

**Carson Pratt**
UC Berkeley — B.A. Data Science & Economics

This project is built using the [Loan Default](https://www.kaggle.com/datasets/yasserh/loan-default-dataset) dataset from Kaggle, and published as a Jupyter notebook.

To access the Jupyter notebook, open the `loan_default.ipynb` file.

**Libraries Used:** `pandas`, `scikit-learn`, `matplotlib`

### Overview

Built a balanced random forest classifier to predict borrower loan default risk on a portfolio of outstanding loans. The project focuses on identifying high-risk loans and evaluating classification tradeoffs in an imbalanced dataset, serving as an early-warning diagnostic tool to directly support institutional loss provisioning.

### Approach

* Cleaned and imputed financial features (credit score, LTV, DTI, interest rate)
* Removed extreme outliers
* Stratified train-test split
* Trained balanced random forest classifier
* Evaluated using confusion matrix, precision, recall, and F1-score

### Results

* **Recall:** 0.93
* **Precision:** 0.77
* **Accuracy:** 0.91
