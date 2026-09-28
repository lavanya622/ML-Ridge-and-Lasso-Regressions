# Ridge & Lasso Regression

## Overview

This project implements **Ridge Regression** and **Lasso Regression** for a regression problem using the California Housing dataset.

Both models are regularized versions of Linear Regression and are used to reduce overfitting and control model complexity.

## Dataset

The dataset contains housing-related features such as:

* MedInc
* HouseAge
* AveRooms
* AveBedrms
* Population
* AveOccup
* Latitude
* Longitude

### Target Variable

* **Median House Value**

The target variable represents the median house value for a particular area.

## Objective

The main objectives of this practical are:

* Implement Ridge Regression
* Implement Lasso Regression
* Apply preprocessing and feature scaling
* Train and evaluate both models
* Compare their regression performance using error metrics

## Workflow

The project follows these steps:

1. Load the dataset
2. Explore and understand the data
3. Separate features and target variable
4. Split the data into training and testing sets
5. Apply feature scaling
6. Train Ridge Regression
7. Generate predictions
8. Evaluate Ridge Regression
9. Train Lasso Regression
10. Generate predictions
11. Evaluate Lasso Regression
12. Compare the results

## Ridge Regression

Ridge Regression is a regularized form of Linear Regression that uses **L2 regularization**.

It adds a penalty to large model coefficients, which helps reduce overfitting and handles multicollinearity between features.

## Lasso Regression

Lasso Regression uses **L1 regularization**.

One important property of Lasso is that it can reduce some feature coefficients to zero, which can help with feature selection.

## Model Evaluation

Both Ridge and Lasso Regression were evaluated using:

* Mean Squared Error (MSE)
* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)
* R² Score

These metrics help measure prediction error and overall model performance.

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Jupyter Notebook / VS Code

## Key Learning

Through this practical, I learned:

* Difference between Linear Regression and regularized regression
* L2 regularization in Ridge Regression
* L1 regularization in Lasso Regression
* Importance of feature scaling for regularized models
* Regression error metrics
* How regularization helps control model complexity

## Conclusion

Ridge and Lasso Regression provide regularized alternatives to standard Linear Regression.

Ridge mainly reduces the magnitude of coefficients, while Lasso can also perform feature selection by shrinking some coefficients toward zero.

This practical helped build an understanding of **regularization techniques for regression models**.

⭐ Part of my Machine Learning Practical Series
