# HighFrequencyPairsTradingStrat
Python code for backtesting a high frequency intraday pairs trading strategy
This is the final project for course FRE7121 Statistical Arbitrage at NYU Tandon School of Engineering. The authors are Zhuping Xu and Xingbo Fu. All rights reserved.

This high frequency pairs trading strategy generates very high cumulative P&L when we back test using intraday data from 8/21/2017 to 3/2/2018. 10 stock pairs are selected from S&P 500 stocks using correlation and cointegration test at the beginning of each month. We test the strategy using frequency of 1 min, 5 min, 10 min and 15 min. We also test using different transaction costs.
