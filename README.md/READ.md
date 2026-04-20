# NSE Halal Portfolio Optimizer

Builds optimized investment portfolios using only Sharia-compliant 
stocks from the Nairobi Securities Exchange.

## What it does
Takes 5 NSE stocks that pass Islamic finance screening, generates 
10,000 random portfolio allocations using Monte Carlo simulation, 
and identifies the optimal mix that maximizes return per unit of risk 
(Sharpe Ratio).

## Key Results
- Optimal portfolio: 37.7% return, 17.8% volatility, Sharpe 2.12
- Optimization added KES 436,565 over equal-weight on a KES 1M investment
- Safest halal portfolio anchored by Safaricom (39%) at 13.6% volatility

## Data Note
Safaricom uses real NSE market data. Other stocks use simulated prices 
based on actual NSE characteristics because free historical NSE data 
is not publicly available.

## Related Project
[NSE Sharia-Compliant Stock Screener](https://github.com/sirajiali-hub/nse-sharia-screener) 
— screens NSE stocks against AAOIFI Islamic finance standards.

## Tech Stack
Python, pandas, numpy, matplotlib, seaborn

## Author
Siraji Ali