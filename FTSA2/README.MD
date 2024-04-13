# README

## Overview
This notebook is designed for an in-depth analysis of financial time series data, focusing on different asset classes like stocks, commodities, and cryptocurrencies. It utilizes various statistical and econometric techniques to examine time series properties such as stationarity, autocorrelation, and volatility.

## Key Components
- **Data Retrieval:** Fetches daily time series data for various assets like NASDAQ, gold, Ethereum from Yahoo Finance.
- **Time Series Analysis:** Implements log transformation, calculates returns, and analyzes time series characteristics using plots.
- **Statistical Testing:** Conducts tests like Augmented Dickey-Fuller and Ljung-Box to assess stationarity and autocorrelation.
- **Model Fitting:** Fits ARIMA models to the data to understand underlying patterns.
- **Forecasting:** Provides forecasting and evaluates forecast accuracy using the Diebold-Mariano test.

## Libraries Used
- `numpy`, `pandas`: For data manipulation and numerical operations.
- `matplotlib.pyplot`, `seaborn`: For data visualization.
- `statsmodels`: For statistical modeling and time series analysis.
- `yfinance`: To fetch financial data from Yahoo Finance.
- `scipy.stats`: For statistical functions.

## Data Analysis Workflow
1. **Data Acquisition:** Retrieves and processes financial data for analysis.
2. **Descriptive Analysis:** Visualizes time series data to identify trends and patterns.
3. **Stationarity Testing:** Applies ADF test to determine the stationarity of the time series.
4. **Autocorrelation Analysis:** Investigates autocorrelation in the series using ACF and PACF.
5. **ARIMA Modeling:** Fits ARIMA models to time series data to capture temporal dependencies.
6. **Forecast Evaluation:** Compares forecasting models using the Diebold-Mariano test.

## Usage
To execute this notebook, ensure that all required libraries are installed and that the Jupyter Notebook environment is correctly set up. The notebook can be run cell by cell to observe each step in the time series analysis process.
