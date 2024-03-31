# README

## Overview
This script conducts a detailed analysis of financial time series data, emphasizing stock price and return characteristics. It's an educational tool for understanding time series analysis in finance using Python.

## Features
- Loads stock price data from various sources.
- Calculates log prices and differentiated log prices.
- Generates time series plots for data analysis.
- Analyzes autocorrelation in stock prices and returns.
- Performs normality and statistical tests on the data.
- Examines volatility and conducts grouped statistical analysis.

## Libraries Used
- `pandas`, `numpy`: Data manipulation and numerical operations.
- `matplotlib.pyplot`: Data visualization.
- `statsmodels`, `scipy.stats`: Statistical modeling and functions.
- `yfinance`, `pandas_datareader`: Data fetching from Yahoo Finance.

## Analysis Workflow
1. Load and preprocess data, including log transformations.
2. Visualize data to identify trends and patterns.
3. Determine serial correlation using ACF and PACF.
4. Conduct normality tests on returns.
5. Analyze volatility patterns.
6. Perform statistical tests for different group sizes.

## Execution
Ensure all dependencies are installed and `Data.xlsx` is in the working directory. Execute the script in a Python environment.
