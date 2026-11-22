# TradePilot AI — Free Automatic Signals v3

## Included
- iPhone-first Progressive Web App (PWA).
- Every-60-second scan while page is open and visible.
- Free public Binance spot kline/candlestick endpoint; no API key.
- Selected pairs: BTC, ETH, BNB, SOL, XRP, DOGE, ADA against USDT.
- Rule-based BUY / SELL / WAIT assessment using closed candles, EMA 9/21, RSI 14, MACD momentum direction, relative volume and ATR.
- Indicative entry, ATR-based stop and 2R target for BUY/SELL setups.
- Signal alert log while app is open.
- Manual quotes for forex, stocks, indices and ETFs.
- Manual risk calculator and local manual watchlist.
- No broker integration, no automatic orders, no paid APIs or subscriptions.

## Important
Signals are educational rule-based technical conditions, not AI predictions or recommendations. The confidence and risk scores are heuristic, not calibrated probabilities. Public endpoint access, rate limits, network conditions and local restrictions may affect scanning. This is not a 24/7 background scanner; iOS pauses browser/PWA work when the app is backgrounded or closed. Alerts are in-app only.

## Install
Host all files over HTTPS (for example GitHub Pages), then open the URL in Safari on iPhone → Share → Add to Home Screen → Add.


## Version 4 — Conservative mode
- Uses closed candles and confirms the selected timeframe with 15-minute and 1-hour trend snapshots.
- Requires trend alignment, RSI range, MACD momentum, ADX >= 20, relative volume >= 1.10x, and room to nearby 20-candle support/resistance before issuing BUY/SELL; otherwise WAIT.
- Checklist score is a rule tally, not a win probability. This is not a guarantee of accuracy or profitability.
- Still signals only, no broker integration or order execution; scans only while the app is open.


## Version 5 — Backtest and paper simulation
- Historical Binance candle backtesting with simplified conservative local-timeframe rules, ATR stop/target, estimated 0.20% round-trip cost, win rate, profit factor, net trade returns and max drawdown.
- Local-only manual paper-trade ledger stored in browser storage.
- Historical rules do not reproduce the full live multi-timeframe system; past results do not predict future performance.
- Signals only: no broker connection and no order execution.
