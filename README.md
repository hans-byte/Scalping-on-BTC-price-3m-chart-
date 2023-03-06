# Scalping-on-BTC-price-3m-chart-

This is a Python script that executes a scalping strategy for Bitcoin (BTC) on the Binance exchange. It first defines several Python libraries such as requests, pandas, and binance. Then, it defines a function called least_squares_ma that calculates the LSMA line based on a moving average.

It then connects to the Binance exchange API using a user key and secret key. It retrieves Bitcoin data every 3 minutes and calculates several technical indicators such as the LSMA, Bollinger Bands, and RSI. It then evaluates the conditions for executing a scalping strategy and executes it if the conditions are met. If no Bitcoin is currently held in the account, it will execute a buy order, and if a Bitcoin position is already open, it will evaluate the presence of a Stop Loss order or if the close price is lower than the LSMA to close it or not.

Finally, it uses the Telegram API to send messages to a specified list of Telegram IDs.
