Stock Market Analysis and Portfolio Optimization

Overview

This project focuses on analyzing historical stock data of key companies and optimizing a portfolio using machine learning techniques. The main objectives are to visualize stock performance, analyze statistical properties, and determine the optimal portfolio allocation to maximize returns while minimizing risk.

Project Structure

data_collection.py: Script to download and preprocess historical stock data using yfinance.
visualization.py: Scripts for various visualizations, including stock price trends, moving averages, trading volumes, and daily return distributions.
analysis.py: Script to perform statistical analysis, including calculating daily returns, generating a correlation matrix, and estimating expected returns and volatility.
optimization.py: Script to simulate multiple portfolios, calculate the Sharpe Ratio, and identify the optimal portfolio allocation.

Data Collection & Preparation

Downloaded historical stock data for Reliance, TCS, Infosys, and HDFC Bank.
Transformed the data into a suitable format for analysis and visualization.

Visualization

Stock Price Trends: Line plots of Adjusted Close Prices over time.
Moving Averages: Charts showing 50-day and 200-day moving averages.
Trading Volume: Bar charts of trading volumes.
Daily Return Distributions: Histograms of daily returns with KDE plots.

Statistical Analysis

Daily Returns: Calculated daily returns for each stock.
Correlation Matrix: Generated a heatmap to show correlations between stock daily returns.
Expected Returns & Volatility: Estimated based on historical data.

Portfolio Optimization

Simulated 10,000 portfolios to identify the optimal risk-return balance using the Sharpe Ratio.
Determined the portfolio with the maximum Sharpe Ratio, providing the best return per unit of risk.

Results

Optimal Portfolio Weights
HDFC Bank: 22.97%
Infosys: 29.13%
Reliance: 8.45%
TCS: 39.45%

Key Metrics

Max Sharpe Return: 24.07%
Max Sharpe Volatility: 15.85%
Max Sharpe Ratio: 1.52
How to Run the Project


Run the scripts in the following order:
python data_collection.py
python visualization.py
python analysis.py
python optimization.py

Dependencies

pandas
yfinance
matplotlib
seaborn
numpy

Conclusion
This project provides a comprehensive analysis of historical stock data and demonstrates the use of machine learning techniques for portfolio optimization. The insights gained from this analysis can be useful for making informed investment decisions.

Acknowledgements
Special thanks to the open-source community for providing the tools and libraries that made this project possible.

