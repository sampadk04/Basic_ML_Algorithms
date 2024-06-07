# image_classification_with_perceptrons

(This project primarily uses the `sklearn` library for implementation)

- In this project, I use the Perceptron Classifier to clasifiy the images in MNIST_784 dataset.
- I do this in two steps:
  - Firstly, I build a binary classifier to classify digits labeled '0' and 'not 0'.
  - Secondly, I combine this classifer 10 times to classify all 10 digits in a "One vs All" fashion to build a multi-class classifier.
- I also test the models with and without cross-validations.
- I also evaluate the models via various metrics and also tried tweaking the threshold to improve the 'Precision' by looking at the PR-Curves.
- I also analyze Precision-Recall in detail.
- I conduct a Grid Search to improve the hyperparameters.
- I also analyze the behaviour of weight vector in the binary classification case, which helps explain the false positive cases to some extent.
- Finally, I also test the multi-class model on handwritten digits of my own.
