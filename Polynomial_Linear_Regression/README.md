## Polynomial Regression  

## Project Overview  
This project focuses on understanding and implementing Polynomial Regression, an extension of Linear Regression that models non-linear relationships between variables. The goal was to learn how linear models can be transformed to capture complex patterns by introducing polynomial features, and to compare results using both Scikit-learn and a custom implementation approach.  

## Datasets Used  
1. Synthetic Dataset  
Generated using NumPy to simulate non-linear relationships and observe how polynomial features improve predictions  

2. Position Salary Dataset  
Source: Kaggle  
Used to demonstrate non-linear growth patterns between position level and salary  

## Technologies Used  
Python  
NumPy  
Pandas  
Matplotlib  
Scikit-learn  

## Steps Performed  
1. Created a non-linear synthetic dataset  
2. Applied Linear Regression to observe underfitting  
3. Transformed features into polynomial features  
4. Trained Polynomial Regression model using Scikit-learn  
5. Visualized differences between linear and polynomial predictions  
6. Built a custom Polynomial Regression approach using NumPy  
7. Compared predictions from Scikit-learn and custom implementation  
8. Evaluated how degree of polynomial affects model performance  

## Model Explanation  
Polynomial Regression transforms the original input features into higher-degree terms and applies linear regression  

y = b0 + b1x + b2x^2 + b3x^3 + ... + bnx^n  

Where  
y = predicted value  
x = input feature  
b0 = intercept  
b1, b2, ..., bn = coefficients of polynomial terms  

## Key Findings  
Polynomial Regression successfully captured non-linear relationships that Linear Regression could not  
Higher-degree polynomials improved fit but risked overfitting  
The custom-built approach produced results similar to Scikit-learn  
Visualization helped clearly understand underfitting vs good fit  

## What I Learned  
Difference between Linear Regression and Polynomial Regression  
How feature transformation enables linear models to learn non-linear patterns  
Impact of polynomial degree on model performance  
Overfitting and underfitting in regression models  
Implementing polynomial regression manually using NumPy  

## Day 04 of ML Journey  
Today I explored how to handle non-linear data using Polynomial Regression and understood how transforming features can significantly improve model performance. Building and comparing models strengthened my understanding of how regression works beyond straight-line assumptions.  
