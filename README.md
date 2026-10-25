# Monte Carlo Stock Price Simulation

## Overview
This project uses Monte Carlo simulation to model possible future stock prices based on historical market data. It generates 10,000 simulated price paths for four stocks listed in the United States and Indonesia.

## Stocks Analyzed
- Apple (AAPL)
- Microsoft (MSFT)
- Bank Central Asia (BBCA.JK)
- Bank Rakyat Indonesia (BBRI.JK)

## Objectives
- Analyze five years of historical stock price data.
- Calculate daily returns and annualized volatility.
- Simulate possible future stock prices over approximately one trading year.
- Estimate potential ending prices and downside risk.
- Visualize simulated price paths and ending price distributions.

## Tools and Technologies
- Python
- Google Colab
- Yahoo Finance
- yfinance
- NumPy
- Pandas
- Matplotlib

## Methodology
1. Retrieve historical stock prices using Yahoo Finance.
2. Calculate daily percentage returns.
3. Estimate average daily returns and volatility.
4. Generate 10,000 simulated price paths per stock over 252 trading days.
5. Analyze simulated ending prices using averages, medians, and percentiles.
6. Estimate the percentage of simulations ending below the starting price.
7. Visualize simulation paths and ending price distributions.

## Key Results
- Monte Carlo simulation charts.
- Simulated ending price distributions.
- Median and average ending price estimates.
- Fifth and ninety-fifth percentile outcomes.
- Estimated probability of ending below the starting price.
- Risk analysis summary tables.

## Limitations
The simulation is based on historical returns and assumes normally distributed daily returns. Actual market behavior may differ, and the results are not guaranteed forecasts.

## Purpose
This project helped me develop practical skills in quantitative finance, statistical modeling, financial risk analysis, and Python-based simulation.

## Disclaimer
This project is for educational purposes only and does not constitute financial advice.
