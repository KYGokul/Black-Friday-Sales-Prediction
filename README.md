# Black-Friday-Sales-Prediction

## Introduction

This project aims to predict customer purchase amounts during Black Friday sales using various machine learning models. The dataset includes customer transaction data with features like demographics, product categories, and historical purchase amounts. The goal is to leverage these features to forecast purchase amounts and create personalized offers for customers.

## Prediction Models

Three different models were employed to predict customer purchase amounts:

### Ridge Regression
- **Description**: Implements linear regression with regularization to prevent overfitting.
- **Suitability**: Ideal for datasets with multicollinearity issues.

### Random Forest (Top Performing Model)
- **Description**: Utilizes ensemble learning by aggregating predictions from multiple decision trees.
- **Suitability**: Effective for handling high-dimensional data and capturing complex relationships.

### XGBoost Regressor
- **Description**: Uses gradient boosting to build an ensemble of decision trees sequentially.
- **Suitability**: Known for high accuracy and adaptability to various data types.

## Evaluation Metrics

The models were evaluated using the following metrics to assess their performance:

- **MSE (Mean Squared Error)**: Measures the average squared difference between predicted and actual values. Lower values indicate better model performance.
- **RMSE (Root Mean Squared Error)**: The square root of MSE, providing a measure of prediction accuracy in the same units as the target variable. Lower values signify better accuracy.
- **R2 Score (Coefficient of Determination)**: Quantifies the proportion of variance in the dependent variable explained by the independent variables. A score of 1 indicates a perfect fit.
- **Adjusted R2**: Adjusts R2 for the number of predictors, penalizing excessive features. Provides a more realistic measure of model fit.
- **MAE (Mean Absolute Error)**: Measures the average magnitude of errors in predictions, without considering their direction.

## Results

The Random Forest model emerged as the top performer, demonstrating high accuracy in predicting purchase amounts. Detailed performance metrics and model comparisons are provided in the notebook.

## Setup

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/black-friday-sales-prediction.git
    cd black-friday-sales-prediction
    ```

## Conclusion and Future Considerations

The Random Forest model provided the most accurate predictions for Black Friday sales. Future work may include:

- Exploring additional features like holiday periods and special events.
- Analyzing daily-level data for more granular insights.
- Enhancing models with advanced techniques and parameter tuning.
