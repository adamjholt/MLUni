# Machine Learning Course Projects

Some coursework adapted from *Hands-On Machine Learning with Scikit-Learn, Keras & TensorFlow 2nd ed. (2019) by Aurélien Géron*.

## Project 1: Classification & K-NN

An exploration of supervised classification and K-Nearest Neighbours (K-NN) algorithms:

- **Part 1: Forest Type Classification (UCI Dataset)**
  - **Data & Preprocessing:** EDA on satellite imagery features using histograms, parallel coordinates, correlation heatmaps, etc.
  - **Binary Classification:** Evaluated Logistic Regression vs. K-NN, analyzing decision boundaries, precision-recall, ROC curves, and cross-validation generalisation.
  - **Multiclass Classification:** Benchmarked Support Vector Machines, Softmax Regression, and multiclass K-NN using grid search parameterisation, confusion matrices, and F1-scores.

- **Part 2: Housing Price Regression (California Housing Dataset)**
  - **Data Pipeline:** Built a scikit-learn preprocessing pipeline for missing value imputation, standard scaling, and one-hot encoding for categorical features.
  - **Regression & Tuning:** Implemented and tuned K-NN Regression, comparing uniform vs. distance-weighted voting schemes, evaluating performance with RMSE.
