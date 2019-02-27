# High Frequency Pairs Trading Strategy

Python code for backtesting a high frequency intraday pairs trading strategy

I develop an intraday high frequency pairs trading strategy based on mean reverting strategy. It generates high cumulative P&L when I back test using intraday data from 8/21/2017 to 3/2/2018. 10 stock pairs are selected from S&P 500 stocks using correlation and cointegration test at the beginning of each month. The strategy is tested using frequencies of 1 min, 5 min, 10 min and 15 min. I also test using different transaction costs.
