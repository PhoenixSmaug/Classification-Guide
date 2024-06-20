# A Guide to Classification with Regression

This repository should serve as a guide book for building classification models. Particular focus is given to reducing problems in real world data, like outliers, high levarage points and collinearity, which are often negelected in simpler guides. The main steps are:

1) Preprocessing
    * Cleaning Data
    * Outlier Detection and Removal
    * Collinearity Detection
2) A priori Model
    * Full-dimensional Regression
    * Residual Plot Analysis
3) Optimization
    * Non-linear Parameters
    * Dimensionality Reduction
    * Model Comparision
    * Bias Specification
4) Validation
    * Cross-Validation

As an illustrative example we will use the famous data set of [Boston housing price data](http://jse.amstat.org/v19n3/decock.pdf) collected by Dean De Cock. The analysis will be done using `scikit-learn` in a Jupyter notebook.

(c) Mia Muessig
