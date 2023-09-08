## Crypto Trading Bot For Bitcoin With NodeJS & Binance API
This project is a simple crypto trading bot that uses the Binance API to buy and sell Bitcoin (BTC) based on some predefined trading strategies. The bot runs on NodeJS and uses the binance-api-node library to interact with the Binance API.

## Features
The bot can execute market orders or limit orders based on the current price and the trading strategy.

## Installation

To run the bot, you need to have NodeJS and npm installed on your system. You also need to have a Binance account and an API key and secret. Follow these steps to install the bot:

1. Clone this repository or download the ZIP file and extract it.
2. Navigate to the project folder and run npm install to install the dependencies.
3. Rename the .env.example file to .env and fill in your Binance API key and secret, as well as your email or Telegram credentials if you want to enable notifications.
4. Edit the config.js file to set your trading parameters, such as the trading pair, the order type, the order size, the risk management, etc.
5. Run node index.js to start the bot.
