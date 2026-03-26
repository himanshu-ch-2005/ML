## Ridge Regression

## Project Overview
This project focuses on understanding and implementing Ridge Regression, a regularized version of Linear Regression that helps prevent overfitting by adding a penalty to large coefficients. The goal was to explore how regularization improves model generalization and stabilizes predictions, especially when dealing with multicollinearity or high-degree features.

## Datasets Used
1. Synthetic Dataset
Generated using NumPy to observe the effect of regularization on overfitted models

2. Position Salary Dataset
Source: Kaggle
Used to analyze how Ridge Regression controls overfitting in polynomial models

## Technologies Used
Python
NumPy
Pandas
Matplotlib
Scikit-learn

## Steps Performed
1. Created or reused a dataset with potential overfitting scenarios
2. Applied Linear/Polynomial Regression to observe overfitting
3. Introduced Ridge Regression with regularization parameter alpha
4. Trained Ridge model using Scikit-learn
5. Visualized model performance with different alpha values
6. Built a custom Ridge Regression implementation using NumPy
7. Compared results between Scikit-learn and custom model
8. Evaluated how regularization strength impacts coefficients and predictions

## Model Explanation
Ridge Regression modifies the Linear Regression cost function by adding an L2 penalty term

y = b0 + b1x + b2x^2 + ... + bnx^n

Cost Function:

J = Σ(y - ŷ)^2 + λ Σ(bi^2)

Where:

y = actual value

ŷ = predicted value

bi = model coefficients

λ (alpha) = regularization strength

## Key Findings
Ridge Regression reduces overfitting by shrinking coefficient values
Higher alpha values lead to simpler models but may underfit
Lower alpha values behave similarly to standard Linear Regression
Regularization improves model stability, especially with polynomial features
Custom implementation closely matched Scikit-learn results

## What I Learned
Concept of regularization and why it is important
Difference between overfitting and well-generalized models
How L2 penalty (Ridge) controls coefficient magnitude
Impact of alpha (regularization strength) on model performance
Implementing Ridge Regression manually using NumPy

## Day 05 of ML Journey
Today I learned how to control overfitting using Ridge Regression. Understanding regularization gave me deeper insight into building more robust and generalizable models. Comparing manual implementation with Scikit-learn helped solidify my understanding of how the algorithm works internally.
