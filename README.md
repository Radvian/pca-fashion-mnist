# pca-fashion-mnist
An iPython notebook written and ran on Google Colab about conducting Decision Tree and PCA on Fashion MNIST dataset.

This notebook aims to demonstrate that conducting data scaling and PCA before doing a classification algorithm can reduce our data dimensionality pretty substantially, which ends up speeding the training process, but without sacrificing a lot of information loss.

As a baseline model, we train a Decision Tree model on the Fashion MNIST model - it reached 78% accuracy in 66 seconds.
If we scale the data and do a PCA with 90% explained variance before training the Decision Tree model, it still reaches 76% accuracy, but in 45 seconds, and we reduce 82% of the number of feature columns.
