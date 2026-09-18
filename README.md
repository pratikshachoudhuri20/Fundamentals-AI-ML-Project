# Iris Flower Classification using Machine Learning

## Project Overview

This project demonstrates a supervised machine learning approach for classifying Iris flowers into three species: Setosa, Versicolor, and Virginica.

The project uses the Iris dataset available through Scikit-learn and a Logistic Regression classification model.

## Objectives

- Load and understand a machine learning dataset.
- Preprocess and standardize input features.
- Train a classification model.
- Predict flower species.
- Evaluate the model using standard classification metrics.

## Technologies Used

- Python
- Scikit-learn
- Logistic Regression
- StandardScaler
- Train-Test Split

## Dataset

The Iris dataset contains 150 samples with four features:

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

The three target classes are:

- Setosa
- Versicolor
- Virginica

The dataset is loaded directly from Scikit-learn, so no separate dataset download is required.

## Project Workflow

1. Load the Iris dataset.
2. Separate input features and target labels.
3. Split the dataset into training and testing sets.
4. Standardize the features.
5. Train a Logistic Regression model.
6. Generate predictions on the test data.
7. Evaluate the model using accuracy, precision, recall, F1-score, and confusion matrix.

## Installation

Make sure Python 3.9 or later is installed.

Install the required dependency using:

```bash
pip install -r requirements.txt
