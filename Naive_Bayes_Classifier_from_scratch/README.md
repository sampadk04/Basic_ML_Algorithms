# Naive Bayes Classifier from Scratch

Welcome to the **Naive Bayes Classifier from Scratch** repository. This project contains implementations of various Naive Bayes classifiers developed from the ground up, with detailed analysis and performance evaluation.

## Implemented Models

### Bernoulli Naive Bayes

The **Bernoulli Naive Bayes** classifier is designed for binary/boolean features. It models the presence or absence of a feature as a binary value, making it suitable for text classification tasks where features are word occurrences (binary word vector).

Key Features:
- Handles binary feature vectors.
- Useful for text classification with binary term presence.
- Suitable for datasets where features are either present or absent.

### Gaussian Naive Bayes

The **Gaussian Naive Bayes** classifier assumes that the features follow a normal (Gaussian) distribution. It is particularly useful for continuous data.

Key Features:
- Assumes normal distribution of features.
- Suitable for continuous data.
- Commonly used in real-world applications where features are not binary.

### Multinomial Naive Bayes

The **Multinomial Naive Bayes** classifier is suited for discrete data and is typically used for document classification. It models the feature vectors as multinomial distributions, where features represent the frequency of occurrence of words.

Key Features:
- Handles discrete data.
- Ideal for document classification and text analytics.
- Models feature vectors based on frequency counts.

## Features

- **Model Analysis**: Comprehensive analysis of each model, including the estimation of weights and inference processes.
- **Training and Evaluation**: Training and performance evaluation of each model in both binary and multi-class setups.