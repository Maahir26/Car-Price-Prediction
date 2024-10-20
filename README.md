# Car Price Prediction Using Machine Learning Regression Algorithms

This project involves developing a regression model to predict car prices based on various descriptive features such as make, model, age, mileage, and condition. This model aims to provide a tool that can predict fair market values for cars, which could be utilized by dealerships, private sellers, and buyers to make informed pricing decisions.

## Data & Problem Description

### Problem Statement:
The primary objective of this project is to develop a machine learning model that can accurately predict the price of cars based on their features. This tool will aid stakeholders in the automotive industry by providing a data-driven basis for pricing cars, ensuring competitive and fair market values are set.

### Data Description:
The dataset used in this project comprises three separate CSV files:
- **Training dataset:** Contains comprehensive details about cars including features and their corresponding market prices. This dataset is used to train the model.
- **Validation dataset:** Serves as a secondary dataset to fine-tune model parameters.
- **Test dataset:** Used to assess the model's performance in a simulated real-world scenario, where the goal is to predict car prices that mimic actual market conditions.

### Data Dictionary:
- **make**: Manufacturer of the car.
- **model**: Specific model of the car.
- **year**: Manufacture year of the car.
- **mileage**: Total miles driven.
- **condition**: Overall condition of the car, rated from poor to excellent.
- **price**: The price of the car (target variable).

## Success Metrics
The effectiveness of our model is measured by its ability to minimize the Mean Squared Error (MSE). A successful model will achieve an MSE lower than 360, ensuring high accuracy in price predictions against actual market values.

## Code and Resources Used
**Python Version:** 3.8  
**Environment:** Miniconda, Jupyter Notebook  
**Packages:** Pandas, Scikit-Learn, NumPy, Matplotlib, Seaborn

## Exploratory Data Analysis (EDA) & Feature Engineering
A thorough exploration and analysis of the data were conducted to understand underlying patterns and relationships. Key steps included:

- **Data Cleaning:** Removed duplicate entries and handled missing values to improve model accuracy.
- **Feature Exploration:** Examined the distributions of various features and their relationships with the car prices using visualizations such as histograms and box plots.
- **Feature Engineering:** Derived new meaningful features and transformed existing ones to enhance model performance.

### Visualizations
- **Histograms:** For distribution of prices and other continuous variables.
- **Box and Distribution Plots:** To identify outliers and understand the spread of the data.

## Model Building & Evaluation
Multiple regression models were tested, including Linear Regression, Ridge, Lasso, and Random Forest Regressor. The models were evaluated based on their MSE and R-squared values to identify the most accurate predictor.

## Model Performance
- **Baseline Model:** Linear Regression was used as a baseline for performance comparison.
- **Enhanced Model:** The Random Forest model outperformed other models, achieving the lowest MSE and highest R-squared value, indicating superior predictive accuracy.

## Conclusion and Future Work
The Random Forest model demonstrated the best performance with an MSE significantly below our target, making it a reliable tool for predicting car prices. Future enhancements could include integrating more granular data, such as location and additional car features, to further improve accuracy.

### Feature Importance
An analysis of feature importance revealed that 'year', 'mileage', and 'make' are the most critical factors in predicting car prices. These insights can assist sellers and buyers in understanding which attributes most significantly impact car valuation.

## How to Use This Project
Instructions for setting up the environment, running the notebook, and utilizing the model for car price predictions are included in the Jupyter Notebook provided in this repository.

Feel free to explore the notebook and adapt the model to your specific needs!


