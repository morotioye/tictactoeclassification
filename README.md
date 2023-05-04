# Tic Tac Toe Classification

This is a machine learning project that performs classification on the Tic Tac Toe dataset using four classification algorithms: K-NN, Logistic Regression, Decision Trees, and Random Forests.

## Dataset

The Tic Tac Toe dataset contains 958 instances of 9 features (each representing a square on the board) and a target variable (positive or negative). The task is to predict whether a given board configuration will lead to a positive or negative outcome.

The dataset is split into three parts: a training set, a validation set, and a test set. Each set contains 319, 320, and 319 instances, respectively.

## Prerequisites

This project requires the following packages to be installed:

- pandas
- numpy
- scikit-learn

These packages can be installed via pip or conda.

## Running the code

To run the code, simply execute the `main.py` file. This will load the data, preprocess it using one-hot encoding, and perform classification using the four algorithms.

The output will display the accuracy or AUROC score for each algorithm on the training, validation, and test sets.
