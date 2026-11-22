# TradePilot AI — Live Trading Edition (Manual Execution)

Free iPhone-friendly PWA for market scanning, manual trade planning, risk estimation and recording completed trades.

## Update GitHub Pages
1. Download and unzip this package.
2. Open the `TradePilot_AI` folder.
3. Upload and replace the files in the root of your existing GitHub Pages repository.
4. Commit changes and wait for GitHub Pages to publish.
5. Open the site in Safari and refresh. The service-worker cache version has changed.

## New features
- Trade plan and position estimate with 0.1–1.0% risk cap.
- Cost-aware size calculation.
- Actual-fill closed-trade ledger with net P/L, win rate, profit factor, average trade and recorded drawdown.
- CSV export and safety checklist.

## Boundaries
- Manual execution only: no broker connection, API keys or order placement.
- Crypto scanner uses public Binance spot candles. Other markets use manually entered quotes.
- Scanner only runs while open; iOS may suspend it.
- Ledger is stored locally on this device/browser. Export backups.
- Position sizing is a simplified GBP 1:1 price-value estimate, not universal for FX, CFDs, futures, options or leveraged products. Verify contract specs, pip/point value, account currency, margin, costs and slippage.
- Stops may slip or gap; risk is not guaranteed to be capped.
- Signals and backtests are not validated trading edges or forecasts.
