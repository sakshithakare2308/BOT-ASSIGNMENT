
This is a simple Python-based trading bot that interacts with Binance Futures Testnet to place MARKET and LIMIT orders.

---

## Setup Instructions

1. Clone the repository or extract ZIP

2. Install dependencies:
   pip install -r requirements.txt

3. Create `.env` file:
   API_KEY=your_api_key
   API_SECRET=your_api_secret

---

##  How to Run

###  Market Order
python cli.py --symbol BTCUSDT --side BUY --type MARKET --quantity 0.001

###  Limit Order
python cli.py --symbol BTCUSDT --side SELL --type LIMIT --quantity 0.001 --price 60000

---

Logs are stored in:
logs/bot.log

Includes:
- API requests
- API responses
- Errors

---
