---
layout: page
title: Research
permalink: /research/
---

## Quantitative Finance Research
My quantitative work focuses on algorithmic model development, portfolio optimization, and systematic factor research applied to equity markets.

* **Portfolio Optimization:** Modular backtesting framework spanning Markowitz mean-variance, CVaR minimization, Black-Litterman, and hierarchical risk parity with robust covariance estimation.
* **Factor Research:** Multi-factor equity screener for Indian markets with z-score normalization and explicit multicollinearity controls across profitability, valuation, quality, and technical signals.
* **Market Monitoring:** Automated weekly pipeline tracking factor performance, macro signals, VIX term structure, and volatility regimes.

<div style="margin-top: 48px;"></div>

<div style="background: #f9f9f9; border-radius: 6px; padding: 24px 28px; margin-bottom: 32px;">
<h3 style="text-align: center; margin-top: 0;">Portfolio Optimization Framework</h3>

Built a modular portfolio construction and backtesting framework spanning Markowitz mean-variance through CVaR minimization with robust covariance estimation. The framework enforces a strict train/test split with quarterly walk-forward rebalancing and explicit transaction cost modeling to prevent look-ahead bias.

On a 10-asset large-cap universe (2020–2026 out-of-sample), the max-Sharpe Markowitz portfolio delivered a 48.3% annualized return (Sharpe 1.25) vs. the equal-weight benchmark's 43.7% (Sharpe 1.34) — higher return but with a deeper max drawdown of -50.8% vs. -42.2%, a classic illustration of MVO's error-maximization problem. The minCVaR optimizer with EWMA covariance reduced max drawdown to -32.6% and annualized volatility to 25.0%, trading raw return for tail-risk control. Phases 3 and 4 — GARCH volatility forecasting and XGBoost return prediction with purged cross-validation — are currently in progress.

<div style="text-align: center; margin: 24px 0 8px 0;">
<img src="/assets/phase2Results.png" alt="Portfolio Strategy Comparison" style="width: 100%; max-width: 780px; border-radius: 4px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">
<p style="font-size: 0.85em; color: #666; margin-top: 8px;">Out-of-sample strategy comparison: Equal-Weight vs. Markowitz MVO vs. minCVaR (EWMA), 2020–2026</p>
</div>

<a href="https://github.com/SaiTarunGanapavarapu/portfolio-optimization-framework" target="_blank">GitHub →</a>
</div>

<div style="background: #f9f9f9; border-radius: 6px; padding: 24px 28px; margin-bottom: 32px;">
<h3 style="text-align: center; margin-top: 0;">Multi-Factor Equity Screener — Indian Markets</h3>

Built a systematic stock screener for Indian equities that ranks Nifty 50/200 and Bank Nifty universes across a 100-point scoring framework spanning five factor groups: profitability (30pts), balance sheet (20pts), valuation (25pts), quality (15pts), and technicals (10pts).

The core design emphasis is signal orthogonality. Redundant factor pairs — Earnings Yield vs. P/E, ROE vs. ROCE, additive trend rules — are collapsed or replaced to prevent the same underlying signal from being credited multiple times. Valuation multiples and growth rates use selective z-score normalization for sector-relative comparison rather than global thresholds. The screener also implements a dedicated scoring branch for financial stocks (banks, NBFCs, insurance) where standard non-financial metrics like current ratio and net debt/EBITDA are replaced with sector-appropriate analogs. Output is exported to Excel with full per-stock score breakdowns.

<div style="text-align: center; margin: 24px 0 8px 0;">
<img src="/assets/swingScreener.png" alt="Swing Trading Screener Output" style="width: 100%; max-width: 780px; border-radius: 4px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">
<p style="font-size: 0.85em; color: #666; margin-top: 8px;">Sample screener output: Nifty 50 ranked by composite factor score</p>
</div>

<a href="https://github.com/SaiTarunGanapavarapu/Swing-Trading" target="_blank">GitHub →</a>
</div>

---

## Process Systems Engineering (Ph.D.)
My doctoral research focuses on deterministic global optimization, mixed-integer nonlinear programming (MINLP), and mathematical modeling of chemical processes. The unifying theme is developing tractable formulations and algorithms that find certified global optima for problems where local solvers fail.

* **Global Optimization:** Branch-and-bound algorithms with tractable convex relaxations for nonconvex MINLPs arising in process design.
* **Surrogate Modeling:** Neural network and symbolic regression architectures to approximate black-box unit operations for use inside optimization frameworks.
* **Nutrient Recovery:** High-fidelity modeling and optimization of electrodialysis systems for wastewater treatment.

<div style="margin-top: 48px;"></div>

<div style="background: #f9f9f9; border-radius: 6px; padding: 24px 28px; margin-bottom: 32px;">
<h3 style="text-align: center; margin-top: 0;">Global Optimization of Electrodialysis for Nutrient Recovery</h3>

Electrodialysis (ED) is governed by coupled nonlinear physics equations whose raw forms — divisions by near-zero concentrations and logarithmic Donnan potential expressions — cause domain violations in standard solvers. This work reformulates these into algebraically equivalent product-form and exponential constraints compatible with the global solver BARON, enabling certified global optima where standard approaches produced incorrect results.

Applying global optimization revealed a strategy that heuristic design had missed entirely: progressively reducing feed flow to the concentrate channel until, at ~2.97 wt% N, the optimal feed split reaches zero — no inlet flow at all, with water sustained purely by osmotic flux across the membrane. This no-feed regime enables 3.9 wt% N product at under 150 $/t-N, an order of magnitude cheaper than reverse osmosis and air stripping alternatives.

Published in *Journal of Water Process Engineering*, 2026. <a href="https://www.sciencedirect.com/science/article/pii/S221471442600098X" target="_blank">Paper →</a> | <a href="https://github.com/SaiTarunGanapavarapu/ED-Opt" target="_blank">Code →</a>
</div>
