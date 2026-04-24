# HSBC-Time-Series-Analysis

## Objective
The objective of this project is to analyze the time-series behavior of HSBC stock prices and returns using statistical techniques. The project focuses on understanding price dynamics, volatility patterns and short-term forecasting in a banking sector context.

## Data
- Source: Yahoo Finance
- Asset: HSBC
- Frequency: Daily prices

## Tools
- Python
- Pandas, numpy
- matplotlib
- statsmodels

## Methodology
- Exploratory data analysis of HSBC stock prices and returns.
- Volatility analysis using rolling window measures.
- Stationarity testing using the Augmented Dickey-Fuller (ADF) test.
- ARIMA modeling for short-term return dynamics.
- Forecast evaluation using a train-test split.
- GARCH modeling to capture time-varying volatility and risk.

## Key Findings 
- HSBC returns exhibit stationarity with limited short-term predictability.
- ARIMA models capture short-term return dynamics but offer modest forecasting power.
- Volatility is highly persistent and clustered, as evidenced by GARCH modeling, highlighting the time-varying risk characteristics of banking stocks.

## Limitations
- Linear modeling assumptions may not capture all market dynamics.
- Structural breaks and macroeconomic regime shifts are not explicitly modeled.
- The analysis focuses on a single institution without macroeconomic variables.

## Future Work
- Extend volatility analysis using asymmetric GARCH variants.
- Incorporate macroeconomic variables for multivariate analysis.
- Analyze interest rate sensitivity relevant to banking-sector risk.

## Project Status
Completed


