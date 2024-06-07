# LSC_from_scratch

- I implement Least Square Classifier (LSC) from scratch.
- I also implement **label encoder** to transform the output labels into usable form (for both binary and multi-class) classification setup.
- I have addressed four types of problems:
    - first with binary linearly separable data without outliers
    - second with binary separable data with outliers
    - third with multiclass separable data (in our case we looked at separating into three classes)
    - fourth with non linearly separable data
- The first three problems (binary and multiclass) could be addressed with basic LSC, while the fourth required additional step of **polynomial transformation** before employing LSC.
- I conclude from the second case that LSC is highly sensitive to the presence of outliers.
- I also analyze how the decision boundaries work, and visualize the same.
