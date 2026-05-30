# Binance Futures Testnet Trading Bot

Simple Python CLI trading bot for Binance Futures Testnet.

## Features
- Market orders
- Limit orders
- BUY / SELL support
- CLI input
- Logging
- Error handling

## Setup

1 Install dependencies

pip install -r requirements.txt

2 Add API keys

export BINANCE_API_KEY=your_api_key
export BINANCE_API_SECRET=your_secret

3 Run bot

MARKET order

python cli.py --symbol BTCUSDT --side BUY --type MARKET --quantity 0.01

LIMIT order

python cli.py --symbol BTCUSDT --side SELL --type LIMIT --quantity 0.01 --price 60000
