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

## Project 2: Decision Trees, Ensemble Voting & Random Forest Regression

An investigation of tree-based models, ensemble methods, and hyperparameter tuning for classification and regression:

- **Part 1: Decision Tree Classification (Breast Cancer Wisconsin Dataset)**
  - **Data & Preprocessing:** Multicollinearity analysis via correlation heatmaps, feature pruning, and stratified splitting for class imbalance.
  - **Model Tuning:** Evaluated overfitting in unconstrained trees, performed regularisation and grid search, reduced false positives by ~50% (test accuracy ~0.95).

- **Part 2: Ensemble Voting Regression (Concrete Slump Test Dataset)**
  - **Data & Preprocessing:** Addressed skew, bimodal distributions, and outliers.
  - **Voting Ensemble:** Combined Linear Regression, SGD Regression, and SVR within a Voting Regressor ensemble for comparison.

- **Part 3: Decision Tree, Random Forest & Bagging Regression (Abalone Dataset)**
  - **Data & Preprocessing:** Used categorical encoding, density estimation, and outlier inspection.
  - **Ensemble Modelling & Feature Importance:** Trained Decision Tree Regressors and Random Forest Regressor models; identified primary predictor and compared against an SVR Bagging Regressor.

