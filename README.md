# Predict_House_Prices_Linear_Regression-
This repository contains a Machine Learning project focused on predicting housing prices using Regression techniques. The project utilizes the classic Boston Housing dataset to build and evaluate models that can estimate the monetary value of residential real estate based on various structural and neighborhood features.
# Project overview
The goal of this project is to implement a supervised learning pipeline to predict the MEDV (Median value of owner-occupied homes in $1000's). This involves data preprocessing, exploratory data analysis (EDA), feature selection, and the application of regression algorithms.
# Dataset
The dataset used is the Boston Housing Dataset, which includes 506 instances and 14 attributes.
Source: Kaggle - Boston CSV
Key Features:
CRIM: Per capita crime rate by town.
RM: Average number of rooms per dwelling.
AGE: Proportion of owner-occupied units built prior to 1940.
LSTAT: Percentage of lower status of the population.
PTRATIO: Pupil-teacher ratio by town.
Target (MEDV): Median value of owner-occupied homes.
# Technologies Used
Language: Python
Libraries: - Pandas & NumPy for data manipulation.
            Matplotlib & Seaborn for data visualization.
            Scikit-learn for model building and evaluation.
Environment: Jupyter Notebook / Google Colab.
# Implementation Steps
1. Data Loading: Importing the CSV data and inspecting its structure.
2. Data Cleaning: Handling missing values and identifying outliers.
3. Exploratory Data Analysis (EDA): Visualizing correlations between features (e.g., Number of Rooms vs. Price).
4. Feature Engineering: Splitting the data into training and testing sets.
5. Model Selection: Implementing regression models such as:
    ->Linear Regression
    ->Decision Tree Regressor
    ->Random Forest Regressor
6. Evaluation: Comparing models using metrics like Mean Squared Error (MSE) and R-squared (R2) score.
# How to Run
1. Clone the repository:
Bash
git clone https://github.com/YourUsername/Predict_House_Prices.git

2. Install dependencies:
Bash
pip install pandas numpy scikit-learn matplotlib seaborn
3. Run the notebook or script to see the predictions.
