---
layout: post
title: "The Weekly Print"
date: 2026-06-19
categories: [quant, weekly]
excerpt: "Auto-generated weekly quant memo: market regime, factor performance, macro signals, and research digest for the week of June 19, 2026."

---

## 1. Market Regime Snapshot

**VIX Term Structure**

| Tenor | Level | vs. Spot |
|-------|-------|----------|
| VIX Spot | 16.4 | — |
| VIX 3M | 20.5 | +4.1 (Contango) |

**Realized vs. Implied Vol:** SPY 20D RV = 16.4%, VIX = 16.4. Spread = -0.0pp (realized vol below implied — calmer than feared).

**Cross-Asset Momentum (1-Month)**

| Asset | 1M Return | Signal |
|-------|-----------|--------|
| SPY (Equity) | +1.0% | 📈 Positive |
| TLT (Bonds) | +3.8% | 📈 Positive |
| GLD (Gold) | -7.3% | 📉 Negative |
| UUP (US Dollar) | +2.1% | 📈 Positive |

**Regime:** Mixed/transitional regime

*Last updated: 2026-06-20 12:48 UTC*

---

## 2. Factor Performance Dashboard

*Source: Ken French Data Library (Low Volatility: USMV ETF proxy)*

*Note: ETF proxy returns include market beta and are not directly comparable to factor-neutral French library returns.*

| Factor | Weekly | 1M | 3M | Mean (52W wkly) | Std (52W wkly) | Z |
|--------|--------|----|----|-----------------|----------------|---|
| Momentum | +2.22% | +10.73% | +12.98% | +0.42% | 2.07% | +0.87 |
| Value | +1.04% | -1.26% | +5.07% | +0.22% | 1.65% | +0.49 |
| Quality | -1.27% | -3.90% | -2.95% | -0.26% | 1.20% | -0.85 |
| Low Volatility | +0.35% | +2.05% | +0.37% | +0.07% | 1.13% | +0.25 |
| Size | -0.94% | +0.44% | +1.51% | +0.13% | 1.27% | -0.84 |

No factor stress signals this week (all within ±2σ).

*Last updated: 2026-06-20 12:48 UTC*


---

## 3. Macro Signal Tracker

| Indicator | Current | 1W Change | Signal |
|-----------|---------|-----------|--------|
| HY Spread (OAS) | 263bps | -17bps | ✅ Tightening |
| IG Spread (OAS) | 74bps | -1bps | ✅ Tightening |
| 2s10s Yield Curve | 0.27% | -0.13% | Normal |
| 3M10Y Yield Curve | 0.63% | -0.04% | Normal |
| Fed Funds Rate | 3.63% | N/A | → |
| HY − IG Spread | 189bps | — | Risk sentiment proxy |

**Macro Summary:** Risk-on macro backdrop

*Last updated: 2026-06-20 12:48 UTC*


---

## 4. Quant Research Digest

Three papers I found worth reading this week:

> **Which Portfolios? The Construction Dependence of Factor Model Performance** — Useong Shin | [arXiv](https://arxiv.org/abs/2606.19550v1)
 
A good reminder that factor performance is highly sensitive to portfolio construction rules like weighting and rebalancing, not just the underlying signal. It highlights why backtest mechanics need to be scrutinized just as much as the factor itself.

>**Fitting Accumulated Stock Returns with Tempered Skew t-Distribution** — Siqi Shao, R. A. Serota | [arXiv](https://arxiv.org/abs/2606.19318v1)

This paper explores how S&P 500 return distributions evolve over multi-day periods, showing that power-law tails temper toward finite values. It offers a useful mathematical framing for handling non-normal skewness in volatility forecasting.

>**How to spot outliers: an Ensemble Anomaly Detection Framework** — Daniil Peysakhovich, Rafał Sieradzki | [arXiv](https://arxiv.org/abs/2606.20079v1)

A highly practical look at unsupervised anomaly detection for real-time risk systems. Given how easily a single bad price scrape can distort an optimization output, layering these kinds of automated filters is an interesting architectural problem.

*Last updated: 2026-06-20 12:48 UTC*

---

## 5. Stat of the Week

*Auto-computed candidates — pick one and add your commentary below.*

| Stat | Value | Context |
|------|-------|---------|
| CBOE Skew Index | 147 | Elevated tail risk (>130) |
| Momentum / Low Vol 20D correlation | 0.30 | No crowding signal (< 0.6) |

The Skew Index is elevated at 147 while the VIX remains relatively low at 16.4. This divergence indicates the options market is actively pricing in a fat left tail despite calm day-to-day realized volatility. It's an interesting regime to observe mathematically, as standard mean-variance models will inherently underestimate risk here compared to metrics that explicitly measure tail density, like CVaR.

*Last updated: 2026-06-20 12:48 UTC*


---

*Generated: 2026-06-20 12:48 UTC*
