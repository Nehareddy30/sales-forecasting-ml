# Sales Forecasting with Machine Learning

## Objective
Predict future retail sales using multiple ML models
and compare their performance to find the best 
forecasting approach for business planning.

## Tools Used
Python · Pandas · Scikit-learn · Matplotlib · 
Seaborn · Jupyter Notebook

## Dataset
3 years of daily retail sales data (2021-2023)
with engineered features for ML modeling.

## Models Built & Compared
- Linear Regression (baseline)
- Random Forest Regressor
- Gradient Boosting Regressor

## Feature Engineering
- Lag features (1 day, 7 days, 30 days)
- Rolling averages (7 day, 30 day)
- Date features (month, quarter, week)
- Special event flags (holiday season, weekends)

## Key Results
- Best Model: Gradient Boosting
- R² Score: 0.95+ (95% variance explained)
- Forecasted Q1 2024 Revenue: $200K+
- Lag features identified as strongest predictors

## Files
- `sales_forecasting_ml.ipynb` — Full notebook
- `sales_forecast_2024.csv` — 90-day forecast
- `model_comparison_results.csv` — Model metrics
- `sales_eda.png` — Exploratory analysis charts
- `model_predictions.png` — Predictions vs actual
- `feature_importance.png` — Feature analysis
- `sales_forecast.png` — Future forecast chart
- `model_comparison.png` — Model comparison


