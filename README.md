![Task: Regression](https://img.shields.io/badge/ML_Type-Regression-lightblue)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-blue?logo=scikit-learn)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

# Multivariable House Price Prediction

Welcome to the **House Price Prediction** project! This is an enhanced version of the classic regression problem using **Multivariable Linear Regression**. Instead of predicting house prices based on just one feature (e.g., square footage), we’re taking a more realistic approach by using **multiple features** such as number of bedrooms, bathrooms, location rating, and age of the house.

This project is a great starting point for showcasing foundational machine learning concepts in your portfolio. It demonstrates data generation, model training, evaluation, and visualization — all using Python.

---

## Project Goals

- Generate a **synthetic housing dataset** with multiple meaningful features.
- Use **Linear Regression** to predict housing prices.
- Train and test the model to evaluate its accuracy and performance.
- Visualize the model predictions vs. actual prices.

---

## Features Used

- `SquareFeet`: Area of the house
- `Bedrooms`: Total number of bedrooms
- `Bathrooms`: Total number of bathrooms
- `LocationScore`: A score (0–10) denoting the quality of the house's location
- `Age`: Age of the house (in years)

These features are used to predict the target variable:

- `Price`: The final predicted price of the house

---

## Technologies Used

| Library       | Purpose                                |
|---------------|----------------------------------------|
| Python        | Core programming language              |
| NumPy         | Data generation and numerical operations |
| Pandas        | Tabular data manipulation              |
| Scikit-learn  | Model training, evaluation, preprocessing |
| Matplotlib    | Visualizing model performance          |

---

Model Evaluation
Train/Test Split: 80/20

Evaluation Metrics:

Mean Squared Error (MSE): Measures average squared difference between actual and predicted prices.

R² Score: Indicates how well data fits the regression model.

---

Output Visualization
Scatter Plot comparing Actual Prices vs Predicted Prices.

Helps visualize the accuracy of the model predictions.

---

Example Workflow
Synthetic Data Creation using NumPy

DataFrame Assembly with Pandas

Train-Test Splitting using train_test_split

Model Training using LinearRegression()

Prediction on the test dataset

Evaluation with MSE and R² Score

Visualization using Matplotlib

---

Learning Outcomes
Handling multivariate data for regression

Building end-to-end ML workflows

Evaluating models using proper metrics

Presenting predictions with visual clarity

---

## ⭐️ Give it a Star

If you found this repo helpful or interesting, please consider giving it a ⭐️. It motivates me to keep learning and sharing!

---
