# PRODIGY_ML_01 : Linear Regression Model for House Price Prediction

This repository contains the code for implementing a **Linear Regression** model to predict the prices of houses based on their **square footage**, **number of bedrooms** and **number of bathrooms**.

## Task Overview

The objective of this task was to predict house prices using the **Kaggle House Prices** dataset. The model was implemented using **Linear Regression** with a focus on:

- Data preprocessing
- Feature selection
- Model evaluation

## Dataset

- **Training Data:** `train.csv`  
- **Test Data:** `test.csv`  
- Both files contain housing data with features like living area, number of rooms, bathrooms, and the target variable `SalePrice`.


## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab / Jupyter Notebook


## 🧠 Model Summary and Evaluation

- **Algorithm**: Linear Regression
- **Framework**: Scikit-learn (`sklearn.linear_model`)
- **Target Variable**: `SalePrice` (house sale price in dollars)
- **Mean Squared Error (MSE)** – Measures average squared difference between predicted and actual values
- **R² Score** – Indicates how well the model explains the variance in house prices

The model learns a linear relationship between features and sale price, enabling accurate predictions and performance evaluation using standard metrics.

## Usage

1. Download the **Kaggle House Prices dataset** (`train.csv`) from [Kaggle](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/dataimport).
2. Place the dataset (`train.csv`) in the root directory of the project.
3. Run the **linear_regression_model.py** script:

   ```bash
   python linear_regression_model.py
   ```

This will:

- Train the Linear Regression model on the data.
- Output the **Mean Squared Error** and **R-squared** values.
- Display visualizations comparing **actual** vs **predicted** prices.

## Results

The model's performance will be displayed through evaluation metrics, and visual plots will showcase the relationship between predicted and actual house prices.





