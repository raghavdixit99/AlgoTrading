# Algorithmic Trading Strategies

## Overview
This repository contains two primary algorithmic trading strategies:
1. **Pair Trading Strategy**: A market-neutral approach that exploits mean-reverting relationships between asset pairs.
2. **ML-Based Trading Strategy**: A machine learning-driven approach that predicts asset price movements using technical indicators and ML models.

Both strategies are designed for systematic trading, incorporating **feature engineering, predictive modeling, and backtesting** to optimize trade execution and risk management.

## Features
- **Pair Trading Strategy**
  - Cointegration-based asset selection
  - Statistical arbitrage framework
  - Rule-based signal generation & execution
- **ML-Based Trading Strategy**
  - Machine learning-driven trade signal generation
  - Walk-forward optimization for adaptive decision-making
  - Technical indicators for enhanced prediction accuracy

## Installation
Ensure you have Python 3.8 or higher installed. Then, install dependencies:

```bash
pip install -r requirements.txt
```

## Strategy Breakdown
### **Pair Trading Strategy**
- **Objective**: Identify and exploit mean-reverting pairs for market-neutral trading.
- **Key Components**:
  - Cointegration Analysis: Detecting pairs with strong statistical relationships.
  - Spread Modeling: Monitoring deviations from equilibrium.
  - Trade Execution: Entering long/short positions based on mean reversion signals.
- **Performance Metrics**:
  - Profit & Loss (P&L)
  - Sharpe Ratio
  - Maximum Drawdown

### **ML-Based Trading Strategy**
- **Objective**: Use machine learning to predict price movements and optimize trade execution.
- **Key Components**:
  - Feature Engineering: Technical indicators (SMA, RSI, MACD, Bollinger Bands, ATR, ADX)
  - ML Models: Random Forest, Gradient Boosting Machines, Ensemble Voting Classifier
  - Walk-Forward Optimization: Periodic retraining for improved robustness
- **Performance Metrics**:
  - Cumulative Return
  - Sharpe Ratio
  - Risk-Adjusted Profitability

## Results & Visualizations
Both strategies include extensive **backtesting and performance evaluation**. Refer to individual strategy READMEs for results:

- **[Pair Trading Results](./pair_trading/README.md)**
- **[ML-Based Trading Results](./ML_based/README.md)**

## Contributing
Contributions are welcome! If you have improvements, please submit a pull request with well-documented changes.

## License
This project is open-source and available under the MIT License.

