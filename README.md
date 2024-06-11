# Basic ML Algorithms

Welcome to the **Basic ML Algorithms** repository! This repository contains a collection of projects demonstrating various machine learning algorithms, implemented from scratch or using libraries such as `sklearn`. Each project includes comprehensive documentation and detailed analyses of the algorithms.

## Table of Contents

1. [Image Classification with Perceptrons](#image-classification-with-perceptrons)
2. [Logistic Regression from Scratch](#logistic-regression-from-scratch)
3. [Least Squares Classifier from Scratch](#least-squares-classifier-from-scratch)
4. [Naive Bayes Classifier from Scratch](#naive-bayes-classifier-from-scratch)
5. [Perceptrons from Scratch](#perceptrons-from-scratch)
6. [Regression Model Selection](#regression-model-selection)

---

## Image Classification with Perceptrons

This project utilizes the `sklearn` library to implement image classification using Perceptron Classifiers on the `MNIST_784` dataset.

### Project Overview

- **Binary Classification:** Building a binary classifier to distinguish between the digit '0' and 'not 0'.
- **Multi-class Classification:** Extending to a multi-class classifier by combining 10 binary classifiers in a "One vs All" fashion to classify all 10 digits.
- **Model Testing and Validation:** Evaluating models with and without cross-validation.
- **Model Evaluation:** Using various metrics and tweaking the classification threshold to improve precision.
- **Hyperparameter Tuning:** Performing Grid Search to optimize hyperparameters.
- **Weight Vector Analysis:** Analyzing the behavior of the weight vector.
- **Custom Data Testing:** Testing the multi-class model on handwritten digits.

### Features

- Binary and Multi-class Classification
- Cross-Validation
- Evaluation Metrics
- Precision-Recall Analysis
- Hyperparameter Tuning
- Weight Vector Analysis
- Custom Data Testing

For detailed documentation, visit the [project page](./image_classification_with_perceptrons/README.md).

---

## Logistic Regression from Scratch

This repository contains an implementation of **binary logistic regression** from scratch, applied to solve several classification problems.

### Features

- **Binary Logistic Regression Implementation**
- **Classification Problems:**
  - Linearly Separable Classes
  - Non-Linear Decision Boundary using polynomial transformation
- **Iterative Optimization Methods:**
  - Gradient Descent
  - Mini Batch Gradient Descent
- **Learning Curves Analysis**
- **Decision Boundary Visualization**
- **Performance Evaluation**
- **Loss Surface Visualization**

For detailed documentation, visit the [project page](./Logistic_Regression_from_scratch/README.md).

---

## Least Squares Classifier from Scratch

This repository contains an implementation of the Least Squares Classifier (LSC) from scratch, with functionality for label encoding for both binary and multi-class classification setups.

### Features

- **Least Squares Classifier Implementation**
- **Label Encoder**
- **Problem Types Addressed:**
  - Binary Linearly Separable Data without Outliers
  - Binary Linearly Separable Data with Outliers
  - Multiclass Linearly Separable Data
  - Non-Linearly Separable Data with polynomial transformation

### Insights

- **Outlier Sensitivity**
- **Decision Boundaries Analysis**

### Visualizations

Visualizations included to help understand decision boundaries formation.

For detailed documentation, visit the [project page](./LSC_from_scratch/README.md).

---

## Naive Bayes Classifier from Scratch

This project contains implementations of various Naive Bayes classifiers developed from the ground up, with detailed analysis and performance evaluation.

### Implemented Models

- **Bernoulli Naive Bayes:** For binary/boolean features.
- **Gaussian Naive Bayes:** Assumes features follow a normal distribution.
- **Multinomial Naive Bayes:** Suited for discrete data, typically used for document classification.

### Features

- Model Analysis
- Training and Evaluation for both binary and multi-class setups

For detailed documentation, visit the [project page](./Naive_Bayes_Classifier_from_scratch/README.md).

---

## Perceptrons from Scratch

This repository contains an implementation of the perceptron classifier from scratch, along with an analysis of its performance on various types of data.

### Features

- **Implementation:** Custom-built perceptron classifier.
- **Analysis:** Examination of the model's performance on different datasets.
- **Learning Curves:** Visualization of the learning process.
- **Decision Boundaries:** Representation of decision boundaries for each dataset type.

For detailed documentation, visit the [project page](./Perceptrons_from_scratch/README.md).

---

## Regression Model Selection

This repository contains a Jupyter notebook that explores various linear regression models using the California Housing Data from `sklearn.datasets`.

### Models Implemented

- **Linear Regression**
  - Ordinary Least Squares
  - Stochastic Gradient Descent (SGD)
- **Polynomial Regression**
- **Regularized Regression Models**
  - Ridge Regression
  - Lasso Regression
  - Elastic Net Regression

### Hyper-parameter Tuning

- Polynomial Degree Tuning
- Regularization Rate Adjustment
- Learning Rate Adjustment
- Grid Search using `GridSearchCV`
- Randomized Search using `RandomizedSearchCV`

### Model Evaluation

- Comparison based on parameter vectors and Mean Absolute Error (MAE)
- Evaluation scores on the test dataset

For detailed documentation, visit the [project page](./regression_model_selection/README.md).
