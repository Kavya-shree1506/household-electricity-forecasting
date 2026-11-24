# Household Electricity Consumption Analysis & Forecasting

## Project Overview

This project focuses on analysing historical household electricity consumption and developing machine learning models to forecast daily electricity usage.

Using time-series data, the project explores consumption patterns, handles missing values, performs feature engineering and evaluates predictive models.

## Objectives

- Analyse historical household electricity consumption.
- Clean and preprocess time-series data.
- Explore hourly and daily consumption patterns.
- Engineer features for forecasting.
- Train and evaluate machine learning models.
- Compare actual and predicted electricity consumption.

## Dataset

**Individual Household Electric Power Consumption Dataset**

Source: [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/235/individual+household+electric+power+consumption)

- Historical data covering December 2006 to November 2010.
- Original measurements recorded at one-minute intervals.
- Nine original attributes.
- Hourly aggregation used for analysis and forecasting.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab

## Project Workflow

1. Dataset collection and extraction
2. Data loading and inspection
3. Missing-value analysis and cleaning
4. Exploratory data analysis
5. Hourly and daily aggregation
6. Time-series feature engineering
7. Chronological training and testing split
8. Machine learning model development
9. Model evaluation and comparison
10. Actual vs predicted visualisation

## Machine Learning Models

- Random Forest Regressor
- Gradient Boosting Regressor
- Previous-day consumption baseline

## Initial Random Forest Results

| Evaluation Metric | Result |
|---|---:|
| MAE | 0.1836 |
| RMSE | 0.2426 |
| R² Score | 0.4680 |

*Results are from the initial model evaluation on the held-out test period.*

## Key Learning Outcomes

- Working with real-world time-series data.
- Handling missing observations and irregular data gaps.
- Creating lag-based and rolling-average features.
- Applying chronological model validation.
- Evaluating regression models using MAE, RMSE and R².

## Project Files

- `household_electricity_forecasting.ipynb` – Complete analysis and model development notebook.
- `README.md` – Project documentation.

## Future Improvements

- Experiment with additional forecasting algorithms.
- Improve model performance through hyperparameter tuning.
- Explore seasonal and weekly consumption patterns.
- Develop an interactive electricity forecasting dashboard.

## Author

**Kavya Shree R Sekar**

[GitHub](https://github.com/Kavya-shree1506) | [LinkedIn](https://www.linkedin.com/in/kavya-shree-r-sekar-07a08833a/)
