# Python Crypto Trading Bot 

A robust command-line trading bot .


## Implementation Note 


The core logic (Client instantiation, Order construction, Error handling) remains architecturally identical to a Futures implementation.

## Features
- **Smart Execution**: Supports MARKET, LIMIT, and STOP_LOSS orders.
- **Safety First**: Environment variable management for API keys.
- **Logging**: Comprehensive transaction logging to \`trading_bot.log\`.


## Tech Stack
- Python
- python-binance
- Colorama (for CLI interface)

## Setup
1. Clone the repo.
2. Install requirements: `pip install -r requirements.txt`
3. Create a `.env` file with `BINANCE_TESTNET_API_KEY` and `BINANCE_TESTNET_API_SECRET`.
4. Run `python main.py`.
