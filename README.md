# LoxeeMatric

Single-file HTML trading dashboard. Multi-exchange (Binance / Bybit / OKX), Monte Carlo path simulation, live indicators, orderbook/whales/liquidation map, multi-TF analyzer, watchlist & alerts.

## Run
1. Download `index.html`
2. Open via local server (recommended for CORS):
   ```
   python -m http.server 8000
   ```
   then go to `http://localhost:8000`

Atau dobel klik `index.html` — sebagian fetch akan auto-fallback lewat CORS proxy publik.

## Features
- 24+ live data sources (price, OB, OI, funding, F&G, whales, LSR)
- Monte Carlo (GBM + GARCH + bootstrap), heatmap, fan, prob cone
- Indicators: RSI, MACD, BB, ATR, EMA, ADX, CCI, Stoch, OBV
- Volume profile (POC/VAH/VAL), liq map, S/R, Fib retracement
- Position sizing calc, journal, multi-TF, watchlist
- Price-aware decimals (BTC 2dp, PEPE 10dp)
- Optional AI thesis via OpenAI-compatible endpoint

Single-file. No build. No deps.
