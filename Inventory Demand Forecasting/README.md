# Inventory Demand Forecasting

## Project Overview
This project focuses on predicting the demand for various items across different store locations. Accurate demand forecasting is crucial for inventory management, ensuring that products are available when customers need them while minimizing excess stock.

## Tech Stack
- **Language:** Python
- **Libraries:** Pandas, NumPy, Scikit-learn, XGBoost, Matplotlib, Seaborn
- **Models Used:** 
  - XGBoost Regressor
  - Random Forest Regressor
  - Linear Regression (Lasso, Ridge)
  - Support Vector Classifier (SVC)

## Key Features
- **Exploratory Data Analysis (EDA):** Visualizing sales trends over time and across different stores/items.
- **Data Preprocessing:** Handling dates, feature engineering for time-based features, and scaling.
- **Model Comparison:** Evaluating multiple regression models to find the most accurate predictor.
- **Performance Metrics:** Using Mean Absolute Error (MAE) and other relevant metrics for evaluation.

## Dataset
The dataset (`StoreDemand.csv`) contains historical sales data including:
- `date`: The date of the sale.
- `store`: The store ID.
- `item`: The item ID.
- `sales`: The number of items sold.

## How to Run
1. Ensure you have the required libraries installed (`pip install pandas scikit-learn xgboost matplotlib seaborn`).
2. Open the `Inventory Demand Forecasting.ipynb` notebook in Jupyter or Google Colab.
3. Run the cells to see the analysis and model results.
