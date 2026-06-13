---
layout: page
title: Research
permalink: /research/
---

## Quantitative Finance Research
My quantitative work focuses on algorithmic model development, portfolio optimization, and market volatility forecasting.
* **Volatility Forecasting:** Implementing GARCH models to predict index volatility and capture market regime shifts.
* **Portfolio Optimization:** Developing historical backtesters using Markowitz mean-variance frameworks and analyzing credit spreads.
* **Market Monitoring:** Automated weekly scraping and structural parsing of macroeconomic signals.

---

<h3 style="text-align: center;">Portfolio Optimization Framework</h3>

Built a modular portfolio construction and backtesting framework spanning Markowitz mean-variance through CVaR minimization with robust covariance estimation. The framework enforces a strict train/test split with quarterly walk-forward rebalancing and explicit transaction cost modeling to prevent look-ahead bias.

On a 10-asset large-cap universe (2020–2026 out-of-sample), the max-Sharpe Markowitz portfolio delivered a 48.3% annualized return (Sharpe 1.25) vs. the equal-weight benchmark's 43.7% (Sharpe 1.34) — higher return but with a deeper max drawdown of -50.8% vs. -42.2%, a classic illustration of MVO's error-maximization problem. The minCVaR optimizer with EWMA covariance reduced max drawdown to -32.6% and annualized volatility to 25.0%, trading raw return for tail-risk control. Phases 3 and 4 — GARCH volatility forecasting and XGBoost return prediction with purged cross-validation — are currently in progress. Codebase on [GitHub](https://github.com/SaiTarunGanapavarapu/portfolio-optimization-framework).

<div style="text-align: center; margin: 30px 0;">
<img src="/assets/phase2Results.png" alt="Portfolio Strategy Comparison" style="width: 100%; max-width: 800px; border-radius: 4px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">
<p style="font-size: 0.9em; color: #666; margin-top: 8px;">Out-of-sample strategy comparison: Equal-Weight vs. Markowitz MVO vs. minCVaR (EWMA), 2020–2026</p>
</div>

<h3 style="text-align: center;">Multi-Factor Equity Screener — Indian Markets</h3>

Built a systematic stock screener for Indian equities that ranks Nifty 50/200 and Bank Nifty universes across a 100-point scoring framework spanning five factor groups: profitability (30pts), balance sheet (20pts), valuation (25pts), quality (15pts), and technicals (10pts).

The core design emphasis is signal orthogonality. Redundant factor pairs — Earnings Yield vs. P/E, ROE vs. ROCE, additive trend rules — are collapsed or replaced to prevent the same underlying signal from being credited multiple times. Valuation multiples and growth rates use selective z-score normalization for sector-relative comparison rather than global thresholds. The screener also implements a dedicated scoring branch for financial stocks (banks, NBFCs, insurance) where standard non-financial metrics like current ratio and net debt/EBITDA are replaced with sector-appropriate analogs. Output is exported to Excel with full per-stock score breakdowns. Codebase on [GitHub](https://github.com/SaiTarunGanapavarapu/Swing-Trading).

---

## Process Systems Engineering (Ph.D.)
My academic research focuses on deterministic global optimization, mixed-integer nonlinear programming (MINLP), and chemical flowsheet modeling.
* **Nutrient Recovery:** High-fidelity modeling and mathematical optimization of electrodialysis systems for wastewater treatment.
* **Surrogate Modeling:** Training artificial neural networks and using symbolic regression architectures to approximate complex chemical unit operations for optimization frameworks.
* **Algorithmic Development:** Applying deterministic global optimization solvers to non-convex chemical engineering design spaces.
