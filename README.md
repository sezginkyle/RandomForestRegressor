# RandomForestRegressor and LinearRegression on Insurance Dataset

This repository contains a simple example comparing **Linear Regression** and **Random Forest Regressor** models on an insurance dataset to predict insurance charges.

## Dataset
The dataset includes features like age, BMI, smoking status, sex, region, and charges (target).

## Description
- The dataset is loaded and categorical variables (`sex`, `smoker`, `region`) are converted into dummy variables.
- The dataset is split into training and testing sets (70% test size).
- Two models are trained and evaluated:
  - Linear Regression
  - Random Forest Regressor
- Finally, a prediction is made on a random sample from the dataset.

## How to Run
1. Make sure you have the required libraries installed:
   ```bash
   pip install pandas scikit-learn
