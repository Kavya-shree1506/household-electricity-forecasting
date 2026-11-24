# Household Electricity Consumption Analysis & Forecasting

## Project Overview

This project focuses on analysing and forecasting household electricity consumption using historical electricity usage data.

The project uses the Individual Household Electric Power Consumption dataset to explore electricity consumption patterns, perform exploratory data analysis, prepare time-series data, and develop machine learning models to predict daily average electricity consumption.

## Project Objectives

- Analyse historical household electricity consumption.
- Identify consumption patterns and trends over time.
- Perform data cleaning and preprocessing.
- Visualise hourly and daily electricity consumption.
- Develop machine learning models for consumption forecasting.
- Evaluate model performance using appropriate metrics.
- Compare actual and predicted electricity consumption.

## Dataset

**Dataset:** Individual Household Electric Power Consumption

**Source:** UCI Machine Learning Repository

The dataset contains household electricity measurements collected over several years.

The analysis primarily uses the `Global_active_power` variable to study electricity consumption.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab
- GitHub

## Project Workflow

### 1. Data Collection
- Obtained the household electricity consumption dataset.
- Loaded the dataset into Google Colab.

### 2. Data Cleaning and Preprocessing
- Handled missing values.
- Converted date and time columns into datetime format.
- Processed the complete dataset in chunks.
- Aggregated hourly electricity consumption.
- Handled isolated missing hourly values while preserving longer missing periods.

### 3. Exploratory Data Analysis
- Analysed electricity consumption statistics.
- Visualised hourly consumption trends.
- Resampled hourly data into daily average consumption.
- Examined consumption patterns over time.

### 4. Feature Engineering
Created forecasting features including:
- Previous day's consumption (`lag_1`)
- Previous week's consumption (`lag_7`)
- Seven-day rolling average
- Day of the week
- Month

### 5. Model Development

The project uses machine learning approaches for daily electricity consumption forecasting:

- Baseline forecasting approach
- Random Forest Regressor
- Gradient Boosting Regressor

### 6. Model Evaluation

The Random Forest model was
