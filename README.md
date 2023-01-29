# StockPricePercentMoves
-A python script to get data for stock tickers from Yahoo finance and calculate stock historic price percentage moves with specified business days defined by the user and report the highest and lowest moves, then generate a CSV report for the stock price moves to further manipulate data in Excel with charts. Use example: Extract highest 20 days stock price percentage move for the past trailing 12 months or more than use the data to sell one month covered call options with strike price above highest stock price percent move. Hence, minimizing the risk of underlying stocks being called away. The script could be retooled for selling puts, as well as buying option calls/puts.

User input - Enter the values of your choosing in the script in the following variables
BUSINESS_DAYS = 20   # Enter here number of business days, every 5 days is equal to 1 week (20 business days = 4 weeks).
STOCK = 'GOOG'   # Enter your Ticker symbol.

Disclaimer: this is not a financial advice, and data accuracy from Yahoo is not guaranteed.
