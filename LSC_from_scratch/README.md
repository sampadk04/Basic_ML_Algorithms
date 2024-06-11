# Least Squares Classifier from Scratch

This repository contains an implementation of the Least Squares Classifier (LSC) from scratch. It includes functionality for label encoding to transform output labels for both binary and multi-class classification setups.

## Features

- **Least Squares Classifier Implementation**: A step-by-step implementation of the LSC algorithm from the ground up.
- **Label Encoder**: Transforms output labels into a usable form for both binary and multi-class classification.
- **Problem Types Addressed**:
  - **Binary Linearly Separable Data without Outliers**
  - **Binary Linearly Separable Data with Outliers**
  - **Multiclass Linearly Separable Data** (e.g., separating into three classes)
  - **Non-Linearly Separable Data** (requires polynomial transformation before applying LSC)

## Insights

- **Outlier Sensitivity**: The LSC is highly sensitive to the presence of outliers, as demonstrated in the second problem type.
- **Decision Boundaries**: Analysis and visualization of decision boundaries for each classification problem.

## Conclusion

The repository provides a comprehensive analysis of how the Least Squares Classifier works under different scenarios. It demonstrates both the strengths and weaknesses of LSC, particularly its sensitivity to outliers and its applicability to various types of classification problems.

## Visualizations

Visualizations are included to help understand how the decision boundaries are formed and how they change with different types of data.