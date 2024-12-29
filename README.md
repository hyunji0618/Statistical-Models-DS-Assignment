# Statistical Models for Data Science

This repository contains assignments from the University of Chicago's "Statistical Models for Data Science" course, focusing on Linear & Logistic Regression and Model Selection.

## Table of Contents

1. [Dummy Variables & Quintic Approximation](#1-dummy-variables--quintic-approximation)
2. [OLS Estimation & Gauss-Markov Theorem](#2-ols-estimation--gauss-markov-theorem)
3. [Linear Regression](#3-linear-regression)
4. [Robust Linear Regression](#4-robust-linear-regression)
5. [Generalized Linear Models & Binomial Regression](#5-generalized-linear-models--binomial-regression)

## 1. Dummy Variables & Quintic Approximation

This section explores the use of dummy variables in linear regression and variable transformations, including polynomial approximations up to the quintic level.

### Topics Covered

- **Dummy Variables in Linear Regression**
  - Single Dummy Variables
  - Interaction Between Dummy and Continuous Variables
  - Methods for Creating Dummy Variables in Python:
    - Manual Creation
    - Using `get_dummies` in pandas
    - Using `OneHotEncoder` from sklearn
    - Using TensorFlow
- **Variable Transformations**
- **Polynomial Approximation**
  - Quadratic to Quintic Approximations

## 2. OLS Estimation & Gauss-Markov Theorem

This section delves into Ordinary Least Squares (OLS) estimation and the Gauss-Markov theorem, which underpins the efficiency of OLS estimators under certain conditions.

### Topics Covered

- Derivation of OLS Estimators
- Assumptions of the Gauss-Markov Theorem
- Proof of the Gauss-Markov Theorem
- Implications for Model Selection

## 3. Linear Regression

An in-depth look at linear regression models, including model fitting, interpretation, and diagnostics.

### Topics Covered

- Simple Linear Regression
- Multiple Linear Regression
- Assumptions and Diagnostics
- Model Evaluation Metrics
- Implementation in Python

## 4. Robust Linear Regression

This section addresses the limitations of traditional linear regression in the presence of outliers and heteroscedasticity, introducing robust regression techniques as solutions.

### Topics Covered

- Limitations of OLS in Non-Ideal Conditions
- Introduction to Robust Regression Methods
- Implementation of Robust Regression in Python
- Comparison with Traditional OLS

## 5. Generalized Linear Models & Binomial Regression

An exploration of Generalized Linear Models (GLMs) with a focus on binomial regression, commonly used for modeling binary outcome variables.

### Topics Covered

- Introduction to Generalized Linear Models
- Link Functions and Their Applications
- Binomial Regression (Logistic Regression)
- Model Fitting and Interpretation
- Implementation in Python
