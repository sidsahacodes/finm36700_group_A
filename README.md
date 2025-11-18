# FINM 36700 2,1 (Autumn 2025) Portfolio and Risk Management Repository

This repository contains three homework assignments focused on asset risk, portfolio construction, and Value-at-Risk methods using weekly return data.

---

## HW1 — Summary Statistics, Correlations, and Efficient Frontier

This notebook introduces foundational portfolio analytics using a set of assets.

Key components:
- Computation of means, volatilities, and Sharpe ratios  
- Covariance and correlation analysis  
- Risk–return scatterplots  
- Efficient frontier construction  
- Tangency (maximum Sharpe) portfolio  

This homework builds intuition around how assets combine to form diversified portfolios.

---

## HW2 — Diversification and Empirical Risk Measures (VaR & CVaR)

This notebook analyzes unconditional risk for AAPL, META, NVDA, and TSLA.

### Topics covered:
- Volatility, empirical VaR(0.05), and CVaR(0.05) for each asset  
- Construction of an equally weighted portfolio  
- Identification of the most volatile asset (TSLA)  
- Rebuilding the portfolio after replacing that asset with a risk-free position  

### Key insight:
Removing TSLA substantially lowers the portfolio’s volatility, VaR, and CVaR, demonstrating how one high-volatility asset can disproportionately drive portfolio risk.

---

## HW3 — Dynamic VaR, Rolling Volatility, and VaR Hit Tests

This notebook introduces *conditional* risk measures that update with recent market information.

### Components:
- Rolling 26-week volatility forecasts  
- Normal-approximation VaR(0.05) and CVaR(0.05)  
- Comparison of conditional vs unconditional risk  
- VaR hit tests using:
  - Expanding-window volatility  
  - Rolling-window volatility  

### Results:
Hit rates cluster around the expected 5% threshold, indicating reasonable VaR calibration.

---

## Contents
- `HW1_sid.ipynb` — Summary statistics, correlations, efficient frontier  
- `HW2_sid.ipynb` — Diversification, VaR, CVaR  
- `HW3.ipynb` — Dynamic VaR and hit testing  

---

This repository demonstrates the progression from basic portfolio statistics to more advanced risk modeling techniques.
