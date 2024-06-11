# Regression Model Selection

This repository contains a Jupyter notebook that explores various linear regression models using the California Housing Data from `sklearn.datasets`. The notebook covers model building, hyper-parameter tuning, and model evaluation.

## Models Implemented

- **Linear Regression**
  - Ordinary Least Squares (using normal equation)
  - Stochastic Gradient Descent (SGD)
- **Polynomial Regression**
- **Regularized Regression Models**
  - Ridge Regression
  - Lasso Regression
  - Elastic Net Regression

## Hyper-parameter Tuning

The following techniques were employed to optimize model parameters:
- **Polynomial Degree Tuning**
- **Regularization Rate Adjustment**
- **Learning Rate Adjustment**
- **Grid Search** using `GridSearchCV`
- **Randomized Search** using `RandomizedSearchCV`

## Model Evaluation

Models were compared based on:
- Parameter vectors
- Mean Absolute Error (MAE) on training, validation (development), and test sets
- Evaluation scores on the test dataset