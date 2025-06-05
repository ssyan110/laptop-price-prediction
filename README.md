# Laptop Price Prediction

This project focuses on building a machine learning regression model to predict laptop prices based on various technical specifications. The dataset used is sourced from a real-world e-commerce platform and includes attributes like brand, processor type, RAM, storage, screen size, and GPU.

## Problem Statement

Accurately estimating the price of a laptop based on its specifications can help consumers make informed decisions and assist retailers in competitive pricing strategies.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib / Seaborn
- Scikit-learn
- Jupyter Notebook

## Features

- Data cleaning and preprocessing (handling missing values, converting text to numerical features)
- Feature engineering (creating new useful variables)
- Exploratory Data Analysis (EDA)
- Log transformation on price for better distribution
- Regression models implemented:
  - Linear Regression
  - Ridge and Lasso Regression
  - Random Forest Regressor
- Model evaluation using R² score and cross-validation
- Hyperparameter tuning with GridSearchCV

## Results

- Best performing model: **Random Forest Regressor**
- Achieved R² score ≈ 0.89 on the test set

## Files Included

- `Regression_Laptop_Price_Prediction.ipynb`: Main notebook containing the full code and analysis

## How to Run

1. Clone the repository
2. Open the notebook in Jupyter or Google Colab
3. Run all cells in order
4. (Optional) Upload or replace the dataset for your own experimentation
