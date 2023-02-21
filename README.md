# EDA-and-Price-Prediction-of-SP500-Stocks
This project falls within the domain of financial economics and makes use of stock price and fundamentals.
We will explore fundamental data of all S&P 500 companies through a set of visualizations carried out using Seaborn and Matplotlib. 
Additionally, we are going to predict the prices of each stock using the economic and financial factors discussed as independent variables (also known as features).
Here, we will use two regression methods - Linear Regression and XGBoost as an ensemble learning algorithm - and compare its predictions perfomance.

## Contents

| File                                       | Description         |
|--------------------------------------------|---------------------|
| `README.md`                                | This README file.   |
| `S&P 500 - EDA and Price Prediction.ipynb` | Python Notebook.    |                                          
| `S&P500_FundamentalData.csv`               | S&P 500 stock data. |                     

## Data

For this project I extracted some fundamental data for all the companies that comprise the S&P 500 from Barchart (https://www.barchart.com/).
List of variables that constitute the dataset (including both qualitative and quantitative data): 
  - Ticker
  - Company
  - Sector
  - Industry
  - Market Capitalization
  - Price
  - 52 Week High
  - 52 Week Low
  - Dividend Yield
  - Price/Sales (P/S)
  - Price/Book (P/B)
  - Price/Earnings (P/E)
  - Earnings per share (EPS)
  - Return on Assets (ROA)
  - Return on Equity (ROE)
  - 5y Revenue Growth
  - 1y Implied Volatility
