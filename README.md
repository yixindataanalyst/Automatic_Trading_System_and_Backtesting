# Automatic_Trading_System_and_Backtesting
I created this project to practice quantitative trading strategies by observing the cyclical characteristics of stock price trends and the correlations of various indicators, identifying commonalities, and quantifying them to form our stock trading strategy. Historical stock market data is abundant and easily downloadable, so we can use the historical data of each stock for backtesting to infer whether our strategy is effective. Please use Python to write a web crawler to crawl historical stock market data for all stocks in the Shanghai and Shenzhen stock markets.

Download historical market data for all Shanghai and Shenzhen stocks to a local database.
Update daily stock market data to the local database.
Use MySQL for the database.
We have crawled and saved all historical market data for A-shares in order to conduct backtesting and verify the effectiveness of the quantitative trading strategy.

Our Automatic_Trading_System_and_Backtesting follows the following logic:

Define the quantitative trading strategy -> Customize the stock pool -> Prepare historical market data -> Implement the strategy -> Conduct backtesting -> Conduct data analysis.

Use the quantitative trading strategy to conduct backtesting on a single stock or mutual fund, and visualize the backtesting results (strategy profit trend, maximum drawdown), and present the trading log (trading date, buy/sell price, trading amount, profit situation - amount/drawdown).
Use the quantitative trading strategy to conduct backtesting on multiple stocks (customizable stock pool), visualize the backtesting results (total strategy profit trend, maximum drawdown), and present the trading log (trading date, buy/sell price, trading amount, profit situation - amount/drawdown).
Optimize the strategy. If there are flaws in the original strategy or the profits do not meet expectations, appropriate fitting will be conducted to achieve optimization goals.
If the strategy is found to be valid, develop an automatic reminder function to monitor the market trends of individual stocks in the stock pool.
