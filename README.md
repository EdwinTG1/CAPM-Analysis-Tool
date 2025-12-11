# CAPM-Analysis-Tool
This project is a financial analysis tool designed to automate the Capital Asset Pricing Model (CAPM) valuation for UK stocks. By integrating real-time data fetching from Yahoo Finance and the Bank of England, the tool calculates critical risk metrics including Beta, Sharpe Ratio to determine if a stock is fairly valued given its risk profile

Key Features

Automated Data Pipeline: Fetches historical equity data via yfinance and dynamically retrieves the current UK 10-year government bond yield (Risk-Free Rate) from the Bank of England.

Statistical Modeling: Uses Ordinary Least Squares (OLS) regression to estimate Beta ($\beta$) and Jensen’s Alpha ($\alpha$) with high precision.

Performance Metrics: Automatically computes Annualised Return, Volatility, Sharpe Ratio, and Treynor Ratio.

Sensitivity Analysis: Models and visualizes the linear relationship between the Risk-Free Rate and Expected Return to stress-test valuations.

Visualization: Generates Security Market Line (SML) plots, regression scatter plots, and risk-return portfolio comparisons.

Installation & Requirements

Ensure you have Python 3.8+ installed. You can install the required dependencies using pip:

pip install pandas numpy matplotlib yfinance statsmodels requests tabulate
