# Walmart Sales Forecasting

## Overview
This project aims to forecast weekly sales for Walmart across various departments and stores using historical sales data. The solution is designed to help Walmart make strategic decisions related to inventory management, staffing, and marketing campaigns.

## Dataset
The dataset includes:
- Weekly sales data across various Walmart stores and departments
- Store-level information such as size and type
- Holiday flags indicating major holidays
- Temperature, fuel prices, CPI, and unemployment rate for each region

## Objectives
- Forecast store-level weekly sales
- Incorporate external features like holidays and economic indicators
- Improve model accuracy using feature engineering and ML algorithms

## Tech Stack
- **Python**
- **Pandas, NumPy** for data processing
- **Matplotlib, Seaborn** for visualization
- **Scikit-learn, XGBoost** for modeling
- **Jupyter Notebook** for experimentation

## EDA & Insights
- Identified seasonal trends and anomalies in sales
- Noted significant sales impact around holiday weeks
- Correlations between economic indicators and store performance

## Model Development
- Trained models using:
  - Linear Regression
  - Random Forest
  - XGBoost Regressor
- Used GridSearchCV for hyperparameter tuning
- Final model evaluated on RMSE and R² Score

## Results
- Achieved [insert metric, e.g., RMSE of 0.15] on validation set
- Sales spikes during holiday weeks accurately predicted
- XGBoost model outperformed other baselines
