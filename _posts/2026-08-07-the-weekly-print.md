---
layout: post
title: "The Weekly Print"
date: 2026-08-07
categories: [quant, weekly]
excerpt: "Auto-generated weekly quant memo: market regime, factor performance, macro signals, and research digest for the week of August 7, 2026."

---

## 1. Market Regime Snapshot

**VIX Term Structure**

| Tenor | Level | vs. Spot |
|-------|-------|----------|
| VIX Spot | 14.9 | — |
| VIX 3M | 20.5 | +5.6 (Contango) |

**Realized vs. Implied Vol:** SPY 20D RV = 14.4%, VIX = 14.9. Spread = -0.5pp (realized vol below implied — calmer than feared).

**Cross-Asset Momentum (1-Month)**

| Asset | 1M Return | Signal |
|-------|-----------|--------|
| SPY (Equity) | +2.4% | 📈 Positive |
| TLT (Bonds) | -1.6% | 📉 Negative |
| GLD (Gold) | +5.7% | 📈 Positive |
| UUP (US Dollar) | -1.1% | 📉 Negative |

**Regime:** Mixed/transitional regime

*Last updated: 2026-08-09 17:22 UTC*


---

## 2. Factor Performance Dashboard

*Source: ETF Proxies (MTUM, VLUE, QUAL, USMV, IWM vs SPY)*

*Note: ETF proxy returns include market beta and are not directly comparable to factor-neutral French library returns.*

| Factor | Weekly | 1M | 3M | Mean (52W wkly) | Std (52W wkly) | Z |
|--------|--------|----|----|-----------------|----------------|---|
| Momentum | +3.25% | -3.70% | +5.36% | +0.50% | 2.74% | +1.00 |
| Value | +3.40% | +1.30% | +13.45% | +1.13% | 2.53% | +0.90 |
| Quality | +2.90% | +3.29% | +7.94% | +0.40% | 1.53% | +1.64 |
| Low Volatility 🚨 | +2.75% | +3.09% | +7.06% | +0.18% | 1.17% | +2.19 |
| Size | +0.05% | -1.39% | +1.07% | +0.23% | 1.56% | -0.11 |

🚨 **Factor Stress:** Low Volatility (z=+2.19) — weekly return ≥ 2σ from trailing mean.

*Last updated: 2026-08-09 17:22 UTC*


---

## 3. Macro Signal Tracker

| Indicator | Current | 1W Change | Signal |
|-----------|---------|-----------|--------|
| HY Spread (OAS) | 271bps | -13bps | ✅ Tightening |
| IG Spread (OAS) | 78bps | -2bps | ✅ Tightening |
| 2s10s Yield Curve | 0.46% | -0.01% | Normal |
| 3M10Y Yield Curve | 0.78% | -0.14% | Normal |
| Fed Funds Rate | 3.63% | N/A | → |
| HY − IG Spread | 193bps | — | Risk sentiment proxy |

**Macro Summary:** Risk-on macro backdrop

*Last updated: 2026-08-09 17:22 UTC*


---

## 4. Quant Research Digest

Three papers I found worth reading this week:

>**From Value Bounds to Policy-Distance and Active-Face Certificates: Same-Grid Duality for Constrained Dynamic Portfolios** — Jeonggyu Huh | [arXiv](https://arxiv.org/abs/2608.05901v1)  

This paper provides a primal-dual framework to identify which constraints are actually binding when solving dynamic portfolios via numerical solvers or neural networks. It offers a useful mathematical diagnostic for verifying how far a numerical policy deviates from the true optimal boundary when exact analytical solutions are unavailable.

>**Cross-Sectional Heterogeneity in LSTM Networks for Financial Time Series** — Julius Döbelt | [arXiv](https://arxiv.org/abs/2608.05755v1)  

The author explores how standard LSTM architectures struggle with financial data because they fail to capture cross-sectional differences between assets. It highlights the importance of adapting deep learning models to handle asset-specific heterogeneity rather than treating an entire equities universe as uniform sequence data.

>**Portfolio Allocation under Heterogeneous Scales and Multifractality** — Shinji Kakinaka et al. | [arXiv](https://arxiv.org/abs/2608.04987v1)  

This research structures a portfolio allocation model using multifractal cross-correlation analysis to handle financial signals that vary by time scale and fluctuation amplitude. It provides a highly mathematical alternative to standard covariance matrices by modeling how asset correlations inherently shift across different time horizons.

*Last updated: 2026-08-09 17:22 UTC*


---

## 5. Stat of the Week

| Stat | Value | Context |
|------|-------|---------|
| CBOE Skew Index | 133 | Elevated tail risk (>130) |

Low Volatility was the main outlier this week (+2.75%, z = +2.19). It's an interesting contrast to see low-vol assets up and Skew above 130 during a week where SPY also finished positive—a good example of why checking factor breakdowns is useful.

*Last updated: 2026-08-09 17:22 UTC*


---

*Generated: 2026-08-09 17:22 UTC*