# Stock-Market-Trend-Forecasting

This project demonstrates how to use Python to download, analyse and forecast stock prices using **Yahoo Finance** data.  The `yfinance` library provides a Pythonic interface to Yahoo's public APIs, allowing you to pull historical price data for any ticker symbol.

## Contents

- `stock_analysis.ipynb` – Jupyter notebook containing the full workflow: data download, exploratory analysis, calculation of returns and moving averages, simple forecasting via exponential smoothing, and performance evaluation.

## Steps to Run

1. Install required packages: `pandas`, `numpy`, `matplotlib`, `seaborn`, `yfinance`, `statsmodels`.
2. Open the notebook in Jupyter Notebook/Lab.
3. Run the cells sequentially; the notebook will download data for Apple (AAPL) from 2015 to 2025.  You can change the `ticker`, `start_date`, and `end_date` variables to analyse other securities.

## Extension Ideas

- Explore other forecasting models (e.g., ARIMA, Prophet, LSTM neural networks).
- Compare multiple stocks or build a portfolio analysis.
- Include external factors (market indices, economic indicators) as additional features.

This project showcases time‑series data handling, visualisation, and forecasting techniques useful for financial analytics.

