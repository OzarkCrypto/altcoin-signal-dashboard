# Altcoin Signal Dashboard

Backtest results for altcoin screening signals on Binance USDT Perpetual Futures.

## Signals
- **Relative Strength**: ALT/BTC ratio MA crossover
- **Volume Structure**: Up-day vs down-day volume ratio
- **Funding Rate**: Contrarian / momentum funding signals

## Universe
- Binance USDT Perpetual Futures
- Open Interest ≥ $5M
- Stablecoins / wrapped tokens excluded

## Data
- `public/results.json`: Full backtest results across 3 configs × 4 periods
- `public/universe.json`: Current universe with OI data
