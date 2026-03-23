# Multiple Linear Regression

## Project Overview

This project focuses on understanding and implementing Multiple Linear Regression using both built-in libraries and a custom-built model. The goal was to learn not just how to use machine learning models, but also how they work internally by building one from scratch and comparing results.

## Datasets Used

1. Synthetic Dataset
   Generated using make_regression from Scikit-learn and used to understand how multiple features affect predictions

2. Diabetes Dataset
   Source: Kaggle
   Contains multiple medical features to predict disease progression

3. Salary Dataset
   Source: Kaggle
   Used again to test the custom model on a simple dataset

## Technologies Used

Python
NumPy
Pandas
Matplotlib
Scikit-learn

## Steps Performed

1. Generated a synthetic dataset using make_regression
2. Applied Multiple Linear Regression using Scikit-learn
3. Loaded and trained model on the Diabetes dataset
4. Built a custom Multiple Linear Regression model from scratch
5. Compared results between Scikit-learn model and custom-built model
6. Tested the custom model on the Salary dataset
7. Evaluated consistency and accuracy of predictions

## Model Explanation

Multiple Linear Regression extends simple linear regression
y = b0 + b1x1 + b2x2 + ... + bnxn

Where
y = predicted value
x1, x2, ..., xn = input features
b0 = intercept
b1, b2, ..., bn = coefficients

## Key Findings

The custom-built model produced results very similar to Scikit-learn
Demonstrated understanding of coefficients calculation and model training logic
Model worked consistently across synthetic data and real-world datasets

## What I Learned

Difference between Simple and Multiple Linear Regression
How regression works internally including math and implementation
Building ML models from scratch using NumPy
Comparing custom models with library implementations
Testing models on different datasets

## Day 02 of ML Journey

Today I moved from using machine learning models to building one from scratch and validating it. This helped me understand how models work internally instead of treating them as black boxes. I will continue exploring more models and improving my understanding step by step
