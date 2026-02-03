# CAPM-Backtest-Analysis
A Python tool for backtesting asset performance using the Capital Asset Pricing Model (CAPM) with 3D visualizations.

# CAPM Analysis and Backtesting Tool

This project provides a comprehensive implementation of the Capital Asset Pricing Model (CAPM) using Python. It allows for the analysis of an asset's performance (defaulting to NVDA) relative to the market (S&P 500) by calculating key financial metrics such as Beta, Alpha, and volatility.

## Overview

The tool fetches historical market data to calculate expected returns based on systematic risk and compares them with actual historical performance. The analysis includes:

- Data retrieval via yfinance for custom tickers and timeframes.
- Calculation of the Capital Asset Pricing Model formula.
- Advanced 3D visualization of Backtest results (Actual vs. Expected returns vs. Volatility).
- Statistical analysis of Alpha distribution (Mean and Median).

## Technical Philosophy
In order to truly master the underlying financial algorithms and the nuances of data manipulation with Python, I used AI as less as possible during development (Tbh I almost used AI only to write this ReadME).

Every part of this project, from the mathematical modeling to the 3D rendering logic in Matplotlib, was written and debugged manually. This approach was essential for me to develop genuine technical skills and to ensure a deep understanding of how the CAPM theory translates into functional code. I used the Matplotlib documentation to help myself with data vizualisation. 

## Requirements

To run this notebook, you will need the following Python libraries:

- pandas
- numpy
- yfinance
- matplotlib
- pandas_datareader

## Installation and Usage

1. Clone the repository:
   git clone https://github.com/your-username/your-repo-name.git

2. Install the necessary dependencies:
   pip install yfinance pandas numpy matplotlib pandas-datareader

3. Open the CAPM.ipynb notebook in Jupyter Lab, Jupyter Notebook, or VS Code and run the cells.

## Visualizations

The project generates four main charts:
1.Beta Function and Distribution.
2.Time Series Analysis of COE and CAPM components.
3.A 3D Scatter Plot: This compares Actual Return, CAPM Expected Return, and Volatility. The color gradient represents the Alpha (outperformance or underperformance).
4.Alpha Distribution: A histogram used to visualize the consistency of the asset's performance over the selected period.
