# Setup Guide
## Prerequisites
- Node.js v18+ or Python 3.10+
- PostgreSQL 15+ (or other database)
- MT5 Manager API access (contact MetaQuotes)
- Market data API key (e.g., OANDA, Alpha Vantage)

## Installation
1. Clone: `git clone https://github.com/your-username/forex-broker-arbitrage.git`
2. Copy `.env.example` to `.env` and add credentials.
3. Install dependencies:
   - Node.js: `npm install`
   - Python: `pip install -r requirements.txt`
4. Run server:
   - Node.js: `npm start`
   - Python: `python src/backend/main.py`

## MT5 Setup
- Request demo server from MetaQuotes (https://www.metaquotes.net).
- Update `.env` with MT5_SERVER, MT5_LOGIN, MT5_PASSWORD.
