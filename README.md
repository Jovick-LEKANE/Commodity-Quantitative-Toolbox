# Commodity Quantitative Toolbox 🛢️💰

This repository contains a suite of quantitative analysis tools specifically designed for Commodity markets (Energy, Metals).

## 🚀 Included Projects

### 1. Option Pricing Engine (Monte Carlo & Black-Scholes)
- Implementation of the **Black-Scholes-Merton** model for theoretical valuation.
- **Monte Carlo simulation** with standard error calculation to validate numerical convergence.
- Full derivation of **Greeks** (Delta, Gamma, Vega, Theta, Rho) for advanced risk management.

### 2. Market Risk - Value at Risk (VaR)
- **Historical VaR** calculation using real-market data (via Yahoo Finance).
- **Backtesting** module to assess model reliability over the last 2 years.

### 3. Quantitative Trading Strategy
- Backtesting of a **Trend Following** strategy (Moving Average Crossover).
- Comparative performance analysis between **Gold (GC=F)** and **Brent Crude Oil (BZ=F)**.
- Integration of **transaction costs** (slippage/commissions) and **Sharpe Ratio** calculation.
  
## 🛠️ Installation
```bash
pip install -r requirements.txt

![Comparaison de Performance](performance_comparison.png)
