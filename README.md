# ROC Trading Strategy with Bayesian Optimization

This repository contains a complete implementation of a trading strategy based on the Rate of Change (ROC) technical indicator, optimized using Bayesian Optimization. The strategy is designed and backtested on historical Bitcoin (BTC-USD) price data, spanning from 2020 to 2024.

## Overview

The project demonstrates how to build a momentum-based trading strategy that uses ROC to generate buy and sell signals. Bayesian Optimization is employed to efficiently tune the strategy’s hyperparameters — specifically, the ROC window size and the buy/sell threshold values — to maximize returns on the training data.

A proper train-test split is used to validate the performance of the optimized strategy on unseen data. The strategy is then backtested with virtual money, tracking portfolio value and trade signals over time.

## Key Features

- Calculation of the Rate of Change (ROC) momentum indicator for signal generation  
- Bayesian Optimization for automated and efficient hyperparameter tuning  
- Detailed backtesting framework including tracking of portfolio value, trades, and signals  
- Visualizations comparing the strategy’s portfolio growth against a simple buy-and-hold benchmark  
- Comprehensive performance evaluation metrics including returns, trade counts, and win rate  

## Purpose

This repository is ideal for traders, data scientists, and developers interested in algorithmic trading and practical applications of optimization techniques. It serves as a foundation for building, tuning, and evaluating simple momentum-based strategies with real market data.
