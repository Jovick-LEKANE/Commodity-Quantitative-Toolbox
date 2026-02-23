# Commodity Quantitative Toolbox 🛢️💰

The goal of this toolbox is to bridge the gap between theoretical financial models and operational market realities. Unlike equities, commodities exhibit unique volatility patterns and geopolitical sensitivity, making them ideal for testing model robustness.

It integrates three main PROJECTS: derivative pricing, risk management, and algorithmic strategy backtesting.

## 🚀 Included Projects

### PROJECT 1:  Option Pricing Engine (Monte Carlo & Black-Scholes)

**Objective**: Analyze the convergence between analytical and numerical pricing methods.

- **Methodology**: Implementation of the Black-Scholes-Merton (BSM) model compared against a Monte Carlo (MC) simulation with 250,000 trajectories
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

![Graph comparing the performance of gold and Brent crude oil](Graph comparing the performance of gold and Brent crude oil.png)
