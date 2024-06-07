# regression_model_selection

- In this notebook, I built different linear regression models using `California Housing Data` fetched from `sklearn.datasets`:
  - Linear regression (with normal equation and iterative optimization (SGD)), Polynomial Regression
  - Regularizarized regression models - Ridge, Lasso, Elastinet
- I tuned polynomial degree, regularization rate and learning rate with hyper-parameter tuning and cross-validation.
- I also employed Grid Search and Randomized Search via `GridSearchCV` and `RandomizedSearchCV`to tune multiple hyperparameters.
- Lastly, I compared different models in terms of their parameter vectors and mean absolute error on train, dev (validation) and test sets, and analyzed their evaluation score on the test dataset.
