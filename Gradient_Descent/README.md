# Gradient Descent & Regression from Scratch

## **Project Overview**

This project focuses on understanding how regression models learn using optimization techniques, specifically **Gradient Descent**. Instead of only using libraries, I implemented different variations of Gradient Descent from scratch and compared them with **Scikit-learn** models.

The goal was to understand how model parameters are updated iteratively to minimize error.

## **Datasets Used**

1. **Synthetic Dataset**  
   Generated using `make_regression` from Scikit-learn and used to understand regression behavior and gradient updates  

2. **Diabetes Dataset**  
   Source: Scikit-learn  
   Used to test regression models on real-world multi-feature data  

## **Technologies Used**

- **Python**  
- **NumPy**  
- **Pandas**  
- **Matplotlib**  
- **Scikit-learn**  

## **Steps Performed**

1. Generated synthetic dataset using `make_regression`  
2. Visualized data using scatter plots  
3. Applied **Linear Regression** using Scikit-learn  
4. Implemented **Gradient Descent** from scratch  
5. Built custom regression models:  
   - Batch Gradient Descent (BGD)  
   - Stochastic Gradient Descent (SGD)  
   - Mini-Batch Gradient Descent (MBGD)  
6. Trained models on the Diabetes dataset  
7. Compared custom models with Scikit-learn implementations  
8. Evaluated performance using **R² Score**  
9. Visualized model learning and parameter updates  

## **Model Explanation**

Gradient Descent is an optimization algorithm used to minimize the cost function by updating model parameters:

### **Update Rules**
m = m - alpha * (∂/∂m)  
b = b - alpha * (∂/∂b)

Where:

- **alpha** = learning rate  
- Gradients are computed from prediction errors  

## **Types of Gradient Descent Implemented**

### **Batch Gradient Descent (BGD)**  
Uses the entire dataset for each update  
Stable but slower  

### **Stochastic Gradient Descent (SGD)**  
Updates parameters for each data point  
Faster but introduces noise  

### **Mini-Batch Gradient Descent (MBGD)**  
Uses small batches of data  
Balances speed and stability  

## **Key Findings**

- Custom Gradient Descent models produced results similar to Scikit-learn  
- Learning rate significantly affects convergence  
- SGD converges faster but is less stable  
- MBGD provides a good balance between performance and stability  
- Visualization improves understanding of model learning  

## **What I Learned**

- How Gradient Descent works mathematically and practically  
- Differences between BGD, SGD, and MBGD  
- Importance of learning rate and iterations  
- How models iteratively reduce prediction error  
- Building ML models from scratch  
- Comparing custom implementations with library models  

## **ML Journey Update**

In this project, I focused on understanding how machine learning models learn using optimization techniques. Implementing Gradient Descent from scratch helped me understand the training process deeply instead of relying on built-in functions.

I will continue exploring more algorithms and improving my understanding step by step.
