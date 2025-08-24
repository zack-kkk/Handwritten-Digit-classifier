# Handwritten-Digit-classifier

Overview

This project demonstrates Handwritten Digit Recognition using a Neural Network built with TensorFlow and Keras. The dataset is based on MNIST-like handwritten digits, where each image is 28x28 pixels. The goal is to classify digits (0–9) with high accuracy using deep learning

The workflow includes several key steps:

Data Loading and Preprocessing – The dataset is loaded from a CSV file, features (pixel values) and labels are separated, and pixel values are normalized to improve model performance.

Train-Test Split and Label Encoding – The data is split into training and testing sets, and the labels are converted into one-hot encoded format for multi-class classification.

Model Design – A Sequential Neural Network is implemented with an input layer of 784 nodes (flattened 28x28 pixels), two hidden layers with ReLU activation, and an output layer with softmax activation for predicting digits (0–9).

Model Training and Evaluation – The model is trained using the Adam optimizer and categorical cross-entropy loss. Accuracy and loss trends are visualized for both training and validation sets.

Performance Metrics – The model’s predictions are evaluated using a confusion matrix and a classification report.

Visualization – Sample predictions with actual and predicted labels are displayed for better understanding.
