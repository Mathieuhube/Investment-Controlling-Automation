Investment Controlling: Portfolio Performance & Attribution

This Jupyter Notebook automates the process of performance tracking and return attribution for a multi-asset investment portfolio. 
Instead of manual data entry, the tool pulls market data from yahoo finance to visualize how specific index exposures contribute to the overall portfolio's growth.

Key Features

- Automated Data Pipeline: Integrates with the yfinance API to fetch historical monthly closing prices for global ETFs (Example here SPY, IEV, EWJ, EWL, EEM, GLD).
- Portfolio Normalization: Automatically re-bases disparate asset prices to a common starting point (1.0) for accurate comparative analysis.
- Performance Attribution: Calculates the Weighted Contribution of each asset class, allowing users to see exactly which markets drove total returns.
