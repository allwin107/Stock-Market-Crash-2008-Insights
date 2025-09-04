# Stock Market Crash 2008 Analysis

This project analyzes stock market data from 2006 to 2010 to understand the impact of the 2008 Global Financial Crisis on selected stock indices and financial sector stocks.

## Project Overview

The 2008 financial crisis was a pivotal event in modern economic history. This analysis focuses on the price movements, volatility, correlation, and maximum drawdown of the following tickers:

- **BAC:** Bank of America Corporation
- **C:** Citigroup Inc.
- **JPM:** JPMorgan Chase & Co.
- **^DJI:** Dow Jones Industrial Average
- **^GSPC:** S&P 500
- **^IXIC:** NASDAQ Composite

The goal is to visualize and quantify the effects of the crisis on these assets and highlight the differences in impact between broad market indices and specific financial institutions.

## Data

The data used in this analysis is historical daily stock market data for the specified tickers from January 1, 2006, to December 31, 2010. The `yfinance` library is used to download this data.

## Analysis Steps

The notebook (`stock_market_2008_analysis.ipynb`) includes the following steps:

1.  **Setup Environment:** Install necessary libraries (`yfinance`, `pandas`, `numpy`, `matplotlib`, `seaborn`).
2.  **Download Stock Market Data:** Download daily closing prices for the selected tickers.
3.  **Basic Cleaning:** Handle missing values in the data.
4.  **Line Plot of Stock Prices:** Visualize the historical price trends of all tickers.
5.  **Focus on 2008 Crash Period:** Plot stock prices specifically during the 2008-2009 crisis period to highlight the sharp declines.
6.  **Rolling Volatility (Standard Deviation):** Calculate and plot the 30-day rolling standard deviation of daily returns to visualize market volatility.
7.  **Correlation Between Stocks:** Compute and visualize the correlation matrix of daily returns to understand how assets moved together during the period.
8.  **Maximum Drawdown (Peak-to-Trough Loss):** Calculate and visualize the maximum percentage drop from a peak to a trough for each ticker, illustrating the extent of losses.

## Key Findings

The analysis reveals:

- A significant decline across all major indices and financial stocks in 2008.
- Financial stocks experienced substantially larger drawdowns compared to the broader market indices.
- Market volatility spiked dramatically during the crisis period.
- Correlations between assets increased, indicating a lack of diversification benefits during the downturn.

## Requirements

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- yfinance
