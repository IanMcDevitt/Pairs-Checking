# Pairs Trading Analysis with Python

This repository contains Python code for conducting Pairs Trading analysis. The analysis process includes data fetching, validation, visualization, correlation and cointegration testing, linear regression to calculate the hedge ratio, spread calculation, and stationarity tests. The code also provides the functionality to fit a GARCH(1, 1) model for volatility estimation.

## Description

The code leverages financial data from Yahoo Finance, calculates daily returns, and tests for correlation and cointegration. It uses linear regression to find the hedge ratio, calculates the spread, and performs the Augmented Dickey-Fuller test on the spread to check for stationarity. It checks autocorrelation in the residuals of the model and fits a GARCH(1, 1) model to the returns. The code also provides visualizations for time series of returns and correlation matrices. Exception handling and data validation steps are implemented throughout the analysis.

The final step in the analysis is to check whether the analyzed stock pair presents a good trading opportunity based on their correlation, cointegration, and stationarity.

## Libraries Used

The code uses the following Python libraries:
- Yfinance for data fetching
- Numpy for numerical calculations
- Pandas for data manipulation
- Statsmodels for statistical modeling
- Matplotlib and Seaborn for data visualization
- Arch for GARCH model implementation

## How to Use

To use this code, clone this repository and run the Python script. You can modify the stock tickers, date range, and other parameters as per your analysis needs. Make sure to install all the required Python libraries before running the script.
