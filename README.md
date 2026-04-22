# Ames House Price Prediction (0.86 R²)
Predicting residential home prices using advanced regression techniques.

## 📊 Project Overview
This project uses the Ames Housing Dataset to predict house prices. I implemented a machine learning pipeline that handles feature engineering, data cleaning, and predictive modeling using XGBoost.

## 🚀 Key Features
* **Feature Engineering**: Created a 'TotalSF' metric with a 0.83 correlation to SalePrice.
* **Data Transformation**: Applied Log-Transformation to the target variable to achieve a Normal Distribution.
* **Advanced Imputation**: Used neighborhood-median imputation for missing physical attributes.
* **Algorithm**: Optimized XGBoost Regressor for final predictions.

## 📈 Results
* **R-Squared**: 0.86
* **Log-RMSE**: 0.13737
