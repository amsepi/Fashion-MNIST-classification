# Fashion-MNIST-classification
Classifying clothing items in the Fashion MNIST dataset using neural network models.
Project Overview
● Approach: Develop two models - one without dimensionality reduction and one with PCA-based dimensionality reduction.
● Objective: Classify clothing items in the Fashion MNIST dataset using neural network models.
Model 1 - Baseline NN
● Designed a simple neural network architecture for classification with 128 neurons in the middle layer
● Trained the model on the training data with appropriate hyperparameter tuning and such as choosing appropriate activation function(relu & softmax)
● Achieved a validation accuracy of approximately 88.64%.
● Test accuracy: 88.11%.

Model 2 - PCA-NN

Trained a new neural network model using the transformed data.
Applied PCA to the training data for dimensionality reduction.
Achieved a validation accuracy of approximately 88.83%.
Chose a suitable number of principal components based on explained variance analysis.
Test accuracy: 88.75%.

Comparison and Analysis

Dimensionality reduction via PCA improved computational efficiency without significantly impacting accuracy.
Both models achieved similar accuracies on the test set.
The PCA-NN model exhibited shorter training time compared to the non-PCA NN model (39.03 seconds vs. 68.27 seconds).
