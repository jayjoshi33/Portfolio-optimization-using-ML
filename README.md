# Portfolio Optimization Project

This repository contains a Jupyter Notebook dedicated to portfolio optimization, a process of selecting the best mix of assets to achieve the desired balance between risk and return. By utilizing historical data and advanced mathematical techniques, this project demonstrates how to construct an efficient portfolio using Python.

## Project Overview
Portfolio optimization is a key concept in financial analysis and investment management. It aims to allocate assets in a way that maximizes returns for a given level of risk or minimizes risk for a given level of expected return. This notebook uses historical stock data to compute various metrics, evaluate portfolio performance, and apply optimization algorithms to identify an optimal allocation.

## Features
- **Data Collection and Preprocessing**: Retrieves and cleans historical financial data for selected assets, ensuring it's ready for analysis.
- **Return and Risk Calculation**: Calculates expected returns and portfolio risk (measured as standard deviation), giving insights into each asset's performance.
- **Efficient Frontier Analysis**: Implements portfolio optimization to plot the efficient frontier, a graph representing the best possible combinations of risk and return.
- **Portfolio Optimization**: Uses algorithms to determine the ideal weight for each asset to maximize the Sharpe ratio or minimize risk.
- **Visualizations**: Plots the efficient frontier, asset allocation, and other key metrics for better understanding.

# Backtesting Results

| Time-period  | Period (Start Date - End Date) | Method          | Average return | Nifty return | Number of stocks |
|--------------|---------------------------------|-----------------|----------------|--------------|------------------|
| 1-week       | 01-01-2023 - 22-09-2023         | Mean-Variance   | 0.61           | 0.27         | 4                |
| 2-weeks      | 13-01-2023 - 22-09-2023         | Max Sharpe      | 1.54           | 0.69         | 9                |
| 1-month      | 22-01-2021 - 22-09-2023         | Equal-weighted  | 2.88           | 1.02         | 8                |
| 3-months     | 22-01-2021 - 22-09-2023         | Equal-weighted  | 7.5            | 3.21         | 13               |


## Installation
To run this notebook, you'll need Python 3.x and the following packages:
- `pandas`
- `numpy`
- `matplotlib`
- `scipy`
- `yfinance` (for stock data)

Install the dependencies using:
```bash
pip install pandas numpy matplotlib scipy yfinance
