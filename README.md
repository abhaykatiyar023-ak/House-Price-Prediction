# 🏠 House Price Prediction using Linear Regression

## 📌 Project Overview

This project predicts house prices using **Machine Learning**.

A **Linear Regression** model is trained on the Housing dataset to predict the price of a house based on different features such as area, number of bedrooms, bathrooms, stories, parking, and other facilities.

## 🎯 Objectives

- Train a Linear Regression model
- Predict house prices
- Evaluate the model using **R² Score**
- Compare actual and predicted house prices using a plot

## 📂 Dataset

The dataset used is `Housing.csv`.

It contains information about houses and their prices.

Some important features are:

- `area`
- `bedrooms`
- `bathrooms`
- `stories`
- `mainroad`
- `guestroom`
- `basement`
- `hotwaterheating`
- `airconditioning`
- `parking`
- `prefarea`
- `furnishingstatus`

### Target Variable

```text
price


🛠️ Technologies Used
Python
Pandas
Matplotlib
Scikit-learn
Google Colab

🤖 Machine Learning Algorithm
Linear Regression

Linear Regression is a supervised machine learning algorithm used to predict a continuous numerical value.

In this project, it is used to predict house prices


🔄 Project Workflow
Housing Dataset
       ↓
Data Loading
       ↓
Data Checking
       ↓
Feature Selection
       ↓
Categorical Data Encoding
       ↓
Train-Test Split
       ↓
Linear Regression Model
       ↓
House Price Prediction
       ↓
R² Score Evaluation
       ↓
Actual vs Predicted Plot


📊 Model Evaluation

The model is evaluated using the R² (R-squared) score.

R² score shows how well the model explains the variation in house prices.

A higher R² score indicates better model performance.

📈 Visualization

The project creates a scatter plot comparing:

Actual House Prices
Predicted House Prices

This helps visualize how close the predictions are to the actual prices.
