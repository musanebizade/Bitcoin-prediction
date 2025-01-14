# Time Series Forecasting with TensorFlow

This project focuses on building a time series forecasting model using TensorFlow. The dataset used contains Bitcoin price data from October 1, 2013, to May 18, 2021. The project involves data preprocessing, visualization, modeling, and evaluation to predict future trends in Bitcoin prices.

## Project Overview

- **Objective**: To forecast Bitcoin prices using time series analysis techniques.
- **Dataset**: Historical Bitcoin prices from CoinDesk, spanning from 2013 to 2021.
- **Tools and Frameworks**:
    - TensorFlow for model development.
    - Pandas for data manipulation.
    - Matplotlib for visualization.

## Steps Involved

1. **Data Loading and Preprocessing**:
    - Loaded the Bitcoin price dataset.
    - Parsed the date column and set it as the index for time series analysis.
    - Renamed columns for clarity and visualized the trends.
2. **Exploratory Data Analysis**:
    - Plotted Bitcoin price trends to understand data patterns and seasonality.
3. **Dataset Splitting**:
    - Created training and testing datasets for the time series.
4. **Model Development**:
    - Designed a TensorFlow-based model for forecasting.
    - Implemented layers suitable for sequential data.
5. **Evaluation**:
    - Assessed model performance using relevant metrics.
