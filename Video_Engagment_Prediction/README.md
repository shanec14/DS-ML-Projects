# Educational Video Engagement Prediction

This Jupyter Notebook contains code to train and evaluate a Logistic Regression model for predicting the engagement level of learners with educational videos using the `videolectures.csv` dataset.

## Dataset

The dataset used in this analysis is `videolectures.csv`. This dataset contains information about educational videos, including features such as title word count, easiness, speaker speed, and silent period rate. Additionally, the dataset includes a binary target variable indicating the engagement level of learners with each video.

## Models

One type of model is evaluated in this notebook:

1. **Logistic Regression**: Logistic Regression is a statistical model that predicts the probability of a binary outcome. It estimates the probability that a given input belongs to a particular class using the logistic function.

## Evaluation

The notebook includes the following steps:

1. **Data Loading and Preprocessing**: Load the dataset and preprocess it as necessary, such as handling missing values and splitting the data into training and testing sets.

2. **Model Training**: Train a Logistic Regression model using the training data.

3. **Model Evaluation**: Evaluate the trained model using various evaluation metrics such as confusion matrix, precision-recall curve, and ROC curve.

## Files

- `videolectures.csv`: Dataset containing information about educational videos and their engagement levels.
- `Educational_Video_Engagement_Prediction.ipynb`: Jupyter Notebook containing code for training and evaluating the model.

## Usage

To run the notebook:

1. Ensure you have Jupyter Notebook installed.
2. Clone or download the repository containing the notebook and the dataset.
3. Open the notebook using Jupyter Notebook.
4. Execute each cell in the notebook sequentially to load the data, train the model, and evaluate its performance.

## Dependencies

The following Python libraries are required to run the notebook:

- `pandas`: For data manipulation and analysis.
- `numpy`: For numerical operations.
- `scikit-learn`: For machine learning algorithms and evaluation metrics.
- `matplotlib`: For data visualisation.
