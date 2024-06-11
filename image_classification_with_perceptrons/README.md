# Image Classification with Perceptrons

This project utilizes the `sklearn` library to implement image classification using Perceptron Classifiers on the `MNIST_784` dataset.

## Project Overview

In this project, we explore the use of Perceptron Classifiers for image classification through the following steps:

1. **Binary Classification:**
   - We first build a binary classifier to distinguish between the digit '0' and 'not 0'.

2. **Multi-class Classification:**
   - We extend the binary classifier to a multi-class classifier by combining 10 binary classifiers in a "One vs All" fashion to classify all 10 digits.

3. **Model Testing and Validation:**
   - We evaluate the models with and without cross-validation to ensure robustness.

4. **Model Evaluation:**
   - Various metrics are employed to evaluate the models, and we tweak the classification threshold to improve precision by examining Precision-Recall (PR) Curves.
   - A detailed analysis of Precision-Recall is also conducted.

5. **Hyperparameter Tuning:**
   - A Grid Search is performed to optimize the hyperparameters of the model.

6. **Weight Vector Analysis:**
   - In the binary classification case, we analyze the behavior of the weight vector, which helps explain some false positive cases.

7. **Custom Data Testing:**
   - Finally, the multi-class model is tested on handwritten digits of our own.

## Features

- **Binary and Multi-class Classification:** Implementation of Perceptron Classifiers for both binary and multi-class classification.
- **Cross-Validation:** Testing the model performance with cross-validation.
- **Evaluation Metrics:** Use of various metrics to evaluate model performance.
- **Precision-Recall Analysis:** Detailed analysis and threshold tuning for precision improvements.
- **Hyperparameter Tuning:** Optimization of hyperparameters using Grid Search.
- **Weight Vector Analysis:** Understanding the model behavior through weight vector analysis.
- **Custom Data Testing:** Evaluation of the model on custom handwritten digits.