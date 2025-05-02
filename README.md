# Quantitative Finance Analysis and backtesting

## Overview

I am passionate about developing quantitative finance applications, focusing on trading strategy development and position sizing optimization. The notebooks implement a Simple Moving Average (SMA) crossover trading strategy and a trading simulator for position sizing using the Kelly Criterion. Together, they provide a robust framework for developing, backtesting, and optimizing trading strategies while evaluating the impact of position sizing and leverage on portfolio performance.

## Components

1. **\[QuantFinance\]Sma\_FineTurningParameter\_Backtesting.py.ipynb**:  
     
   - Implements an SMA crossover trading strategy for Tesla (TSLA) stock.  
   - Fetches historical price data, backtests the strategy, and optimizes SMA parameters to maximize the Sharpe Ratio.  
   - Includes multithreaded optimization to efficiently explore a large parameter space.

   

2. **\[QuantFinance\]PositionStrategy.ipynb**:  
     
   - Analyzes optimal position sizing using the Kelly Criterion for a 50% win rate scenario.  
   - Provides a Dash-based trading simulator to visualize the impact of different bet sizes and leverage levels on capital growth and drawdowns.  
   - Solves mathematical formulations to determine the optimal bet fraction and expected capital after trades.

## Features

- **Data Fetching**: Retrieves TSLA stock data for 2024 from the FinMindTrade API.  
- **Strategy Development**: Implements an SMA crossover strategy with customizable fast and slow SMA periods.  
- **Backtesting**: Evaluates strategy performance with metrics like return, Sharpe Ratio, and max drawdown.  
- **Parameter Optimization**: Uses grid search and multithreading to find optimal SMA periods.  
- **Position Sizing**: Applies the Kelly Criterion to optimize bet sizes and simulates trading outcomes with varying leverage.  
- **Interactive Visualization**: Dash app provides interactive sliders and graphs to explore position sizing impacts.

---

