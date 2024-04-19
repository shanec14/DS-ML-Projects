# Mushroom Classification Project

This project aims to train and evaluate machine learning models for classifying mushrooms as poisonous or edible based on various features using the mushroom dataset (`mushroom.csv`).

## Dataset

The dataset used in this analysis is [UCI Mushroom Data Set](http://archive.ics.uci.edu/ml/datasets/Mushroom?ref=datanews.io) contained within the `mushrooms.csv` file. It contains information about various features of mushrooms, such as cap shape, cap color, odor, etc., along with a binary target variable indicating whether a mushroom is poisonous or edible.

## Decision Tree Classifier

In this project, a Decision Tree Classifier is trained to predict whether a mushroom is poisonous or not based on the features provided in the dataset. The following steps are performed:

1. **Data Loading and Preprocessing**: Load the dataset and preprocess it, and split it into training and test data.
2. **Model Training**: Train a Decision Tree Classifier using the preprocessed data.
3. **Feature Importance**: Evaluate the importance of features using the trained Decision Tree Classifier.
4. **Visualization**: Visualize the feature importance to understand which features contribute the most to the classification.

## Support Vector Classifier (SVC) with Gamma Optimization

Additionally, a Support Vector Classifier (SVC) is trained and optimized using a range of gamma values through cross-validation. The following steps are executed:

1. **Model Training and Optimization**: Train and optimize the SVC model using a range of gamma values and cross-validation.
2. **Evaluation**: Evaluate the performance of the SVC model using training and testing datasets for each gamma value.
3. **Visualization**: Visualize the training and testing scores for each gamma value to understand the impact of gamma on model performance.

## Files

- `mushroom.csv`: Dataset containing information about mushrooms.
- `Mushroom_Classification.ipynb`: Jupyter Notebook containing code for training, evaluating, and visualizing the models.

## Usage

To run the notebook:

1. Ensure you have Jupyter Notebook installed.
2. Clone or download the repository containing the notebook and the dataset.
3. Open the notebook using Jupyter Notebook.
4. Execute each cell in the notebook sequentially to load the data, train the models, and visualize the results.

## Dependencies

The following Python libraries are required to run the notebook:

- `pandas`: For data manipulation and analysis.
- `numpy`: For numerical operations.
- `scikit-learn`: For machine learning algorithms and evaluation metrics.
- `matplotlib`: For data visualization.
