# Experiment 2: Loan Amount Prediction using Regression Models

This experiment explores the application of **regression models** for predicting loan amounts based on applicant features.

## Dataset

* Source: [Predict Loan Amount Dataset (Kaggle)](https://www.kaggle.com/datasets/phileinsophos/predict-loan-amount-data)
* Note: The dataset contains missing values (`NaN`), which must be handled during preprocessing.

## Models Used

The following regression models are implemented and compared:

1. **Linear Regression**
2. **Polynomial Regression**
3. **Ridge Regression**
4. **Lasso Regression**
5. **Decision Tree Regressor**
6. **AdaBoost Regressor**
7. **Gradient Boosting Regressor**
8. **Extreme Gradient Boosting (XGBoost) Regressor**
9. **K-Nearest Neighbors (KNN) Regressor**
10. **Random Forest Regressor**

## Steps Involved

1. Data preprocessing (handling `NaN` values, encoding, scaling).
2. Splitting dataset into training and testing sets.
3. Training different regression models.
4. Evaluating performance using metrics such as **R² Score, Mean Squared Error (MSE), and Root Mean Squared Error (RMSE)**.
5. Comparing results to identify the best-performing model.
