# Polynomial Regression and Model Comparison

This Jupyter Notebook contains code to perform polynomial regression on a dataset of synthetic data points and compare the results with other regression models.

## Dataset

The synthetic dataset used in this analysis consists of input features `x` and target variable `y`. The dataset is split into training and testing sets using the `train_test_split` function from scikit-learn.

## Polynomial Regression

1. **Model Training**: Polynomial regression models of various degrees (1, 3, 6, and 9) are trained using the training data.
2. **Visualization**: The trained models are visualized along with the training and testing data to observe the fitting behavior at different degrees.
3. **Evaluation**: The R² scores are calculated for each polynomial regression model on both the training and testing sets to evaluate the model performance.

## Model Comparison

In addition to polynomial regression, two other regression models are trained and compared:

1. **Linear Regression**: A non-regularized linear regression model is trained and evaluated.
2. **Lasso Regression**: A Lasso regression model with regularization is trained and evaluated.

The R² scores of the polynomial regression, linear regression, and Lasso regression models on the testing set are compared to understand the relative performance of each model.

## Files

- No specific dataset file is used, as synthetic data is generated within the notebook.
- `Polynomial_Regression_and_Comparison.ipynb`: Jupyter Notebook containing code for polynomial regression and model comparison.

## Usage

To run the notebook:

1. Ensure you have Jupyter Notebook installed.
2. Execute each cell in the notebook sequentially to generate synthetic data, train the models, and visualize the results.

## Dependencies

The following Python libraries are required to run the notebook:

- `numpy`: For numerical operations.
- `pandas`: For data manipulation and analysis.
- `matplotlib`: For data visualization.
- `scikit-learn`: For machine learning algorithms and evaluation metrics.
