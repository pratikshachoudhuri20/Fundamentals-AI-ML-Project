# Iris Flower Classification using Machine Learning

## Project Overview

This project demonstrates a supervised machine learning approach for classifying Iris flowers into three species: Setosa, Versicolor, and Virginica.

The project uses the Iris dataset available through Scikit-learn and a Logistic Regression classification model.

## Objectives

* Load and understand a machine learning dataset.
* Preprocess and standardize input features.
* Train a classification model.
* Predict flower species.
* Evaluate the model using standard classification metrics.

## Technologies Used

* Python
* Scikit-learn
* Logistic Regression
* StandardScaler
* Train-Test Split

## Dataset

The Iris dataset contains 150 samples with four features:

* Sepal Length
* Sepal Width
* Petal Length
* Petal Width

The three target classes are:

* Setosa
* Versicolor
* Virginica

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
```

## Dependencies

The project requires:

* scikit-learn

All required dependencies are listed in `requirements.txt`.

## How to Run

Open a terminal in the project folder and run:

```bash
python iris_classification.py
```

The program will load the Iris dataset, train the Logistic Regression model, generate predictions, and display the evaluation results.

## Project Files

* `iris_classification.py` - Main machine learning program.
* `iris_classification.ipynb` - Google Colab/Jupyter notebook containing the project workflow.
* `requirements.txt` - Required Python dependency.
* `README.md` - Project documentation.

## Model

The project uses Logistic Regression as the classification algorithm.

Before training, the input features are standardized using StandardScaler. The dataset is divided into 80% training data and 20% testing data.

## Evaluation

The trained model is evaluated using:

* Accuracy
* Precision
* Recall
* F1-score
* Confusion Matrix

These metrics are used to measure the classification performance of the model.

## Conclusion

This project demonstrates the basic machine learning workflow of data loading, preprocessing, model training, prediction, and evaluation using a classification algorithm on the Iris dataset.

