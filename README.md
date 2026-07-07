# Support Vector Regression (SVR)

## Overview

This project demonstrates **Support Vector Regression (SVR)**, a supervised machine learning algorithm used to predict **continuous numerical values**. Unlike Linear Regression, which fits a line to minimize prediction errors, SVR aims to find a function that fits the data within a specified error margin (called **epsilon, ε**) while maximizing the margin around the regression function.

SVR is particularly effective for modeling **non-linear relationships** by using kernel functions, making it suitable for datasets where Linear Regression cannot accurately capture the underlying patterns.

---

## How SVR Works

Support Vector Regression attempts to fit the best possible regression curve while allowing prediction errors within a predefined margin (ε). Only the data points lying outside this margin, known as **support vectors**, influence the position of the regression curve.

The model can learn both linear and non-linear relationships using kernel functions such as:

- Linear Kernel
- Polynomial Kernel
- Radial Basis Function (RBF) Kernel
- Sigmoid Kernel

In this project, the **RBF (Radial Basis Function)** kernel is used, which is the default kernel in Scikit-learn and is well-suited for capturing non-linear patterns.

---

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

---

## Project Workflow

### 1. Importing the Libraries
### 2. Importing the Dataset
### 3. Feature Scaling
### 4. Training the SVR Model
### 5. Predicting a New Result
### 6. Visualizing the SVR Results
### 7. High-Resolution Visualization

---

## Conclusion

This project demonstrates how **Support Vector Regression (SVR)** can effectively model complex, non-linear relationships between variables. By applying feature scaling and using the RBF kernel, the model learns patterns that traditional Linear Regression may not capture. The visualizations and predictions illustrate the ability of SVR to provide accurate regression results for non-linear datasets, making it a powerful technique for continuous value prediction.
