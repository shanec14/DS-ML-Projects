# Fraud Detection Models Evaluation

This Jupyter Notebook contains code to train and evaluate Support Vector Classifier (SVC) and Logistic Regression models for fraud detection using the fraud_data.csv dataset.

## Dataset

The dataset used in this analysis is `fraud_data.csv`. This dataset contains information about various features related to financial transactions, along with a binary target variable indicating whether a transaction is fraudulent or not.

## Models

Two types of models are evaluated in this notebook:

1. **Support Vector Classifier (SVC)**: SVC is a powerful classification algorithm commonly used for binary classification tasks. It works by finding the optimal hyperplane that best separates the classes in the feature space.

2. **Logistic Regression**: Logistic Regression is a statistical model that predicts the probability of a binary outcome. It estimates the probability that a given input belongs to a particular class using logistic function.

## Evaluation

The notebook includes the following steps:

1. **Data Loading and Preprocessing**: Load the dataset and split the data into training and testing sets.

2. **Dummy Model Training**: Train dummy model to compare trained models evaluation metrics against.

2. **Model Training**: Train SVC and Logistic Regression models using the training data.

3. **Model Evaluation**: Evaluate the trained models using various evaluation metrics such as accuracy, precision, recall, and ROC-AUC score and compare scores to dummy model.

4. **Visualisation**: Visualize the performance of the models using ROC curve and Precision-Recall curve.

## Files

- `fraud_data.csv`: Dataset containing information about financial transactions.
- `Fraud_Detection_Classifiers.ipynb`: Jupyter Notebook containing code for training and evaluating the models.

## Usage

To run the notebook:

1. Make sure you have Jupyter Notebook installed.
2. Clone or download the repository containing the notebook and the dataset.
3. Open the notebook using Jupyter Notebook.
4. Execute each cell in the notebook sequentially to load the data, train the models, and evaluate their performance.

## Dependencies

The following Python libraries are required to run the notebook:

- `pandas`: For data manipulation and analysis.
- `numpy`: For numerical operations.
- `scikit-learn`: For machine learning algorithms and evaluation metrics.
- `matplotlib`  For data visualization.

