# A Guide to Classification with Regression

This repository should serve as a guide book for building classification models. Particular focus is given to reducing problems in real world data, like outliers, high leverage points and collinearity, which are often neglected in simpler guides. The main steps are:

1) Preprocessing
    * Cleaning Data
    * Collinearity Detection
2) A priori Model
    * Full-dimensional Regression
    * Dimensionality Reduction
    * Non-linear Parameters
3) Optimization
    * Model Comparison
    * Bias Specification
4) Validation
    * Cross-Validation

As an illustrative example we will use the "Credit Card Fraud Detection" dataset published [here](https://www.kaggle.com/dsv/6492730), containing over 550,000 records of European cardholders in 2023. The analysis will be done using the Python library `scikit-learn` in a Jupyter notebook.

(c) Mia Muessig
