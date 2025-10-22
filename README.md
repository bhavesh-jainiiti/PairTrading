# Statistical Arbitrage — Cointegration-based Pairs Trading
Pairs trading is a mean-reversion strategy that benefits from being market-neutral — it remains largely hedged against broad market movements. When implemented with rigorous statistical analysis, it can generate strong alpha (returns independent of the market).

At its core, pairs trading relies on identifying two securities, say X and Y, that share a strong economic or fundamental relationship — for example, companies in the same industry, supply chain, or sector. The idea is to model this relationship mathematically.

When the relative prices of these two securities diverge from their typical relationship (as measured by the model), the strategy takes positions expecting that they will revert to their historical equilibrium. This allows the trader to profit from temporary mispricings while maintaining a balanced exposure to the overall market.


Description:
------------
Modular implementation of a cointegration-based pairs trading system.

Features:
- Automatic cointegration detection
- Dynamic z-score computation
- Signal generation and portfolio backtesting
- Performance metrics and visualization
- Mean-reversion (z-score) visualization

Dependencies:
-------------
pip install numpy pandas yfinance statsmodels scipy matplotlib
"""
