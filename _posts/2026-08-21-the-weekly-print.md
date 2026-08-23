---
layout: post
title: "The Weekly Print"
date: 2026-08-21
categories: [quant, weekly]
excerpt: "Auto-generated weekly quant memo: market regime, factor performance, macro signals, and research digest for the week of August 21, 2026."

---

## 1. Market Regime Snapshot

**VIX Term Structure**

| Tenor | Level | vs. Spot |
|-------|-------|----------|
| VIX Spot | 15.1 | — |
| VIX 3M | 18.5 | +3.4 (Contango) |

**Realized vs. Implied Vol:** SPY 20D RV = 13.2%, VIX = 15.1. Spread = -1.9pp (realized vol below implied — calmer than feared).

**Cross-Asset Momentum (1-Month)**

| Asset | 1M Return | Signal |
|-------|-----------|--------|
| SPY (Equity) | +3.6% | 📈 Positive |
| TLT (Bonds) | -1.0% | 📉 Negative |
| GLD (Gold) | +13.8% | 📈 Positive |
| UUP (US Dollar) | -2.4% | 📉 Negative |

**Regime:** Mixed/transitional regime

*Last updated: 2026-08-23 10:58 UTC*


---

## 2. Factor Performance Dashboard

*Source: ETF Proxies (MTUM, VLUE, QUAL, USMV, IWM vs SPY)*

*Note: ETF proxy returns include market beta and are not directly comparable to factor-neutral French library returns.*

| Factor | Weekly | 1M | 3M | Mean (52W wkly) | Std (52W wkly) | Z |
|--------|--------|----|----|-----------------|----------------|---|
| Momentum | -3.80% | -2.81% | +1.11% | +0.48% | 2.81% | -1.52 |
| Value | -0.76% | +3.54% | +9.90% | +1.11% | 2.55% | -0.73 |
| Quality | -1.16% | +3.34% | +5.11% | +0.36% | 1.54% | -0.99 |
| Low Volatility | +0.10% | +5.33% | +5.73% | +0.16% | 1.16% | -0.06 |
| Size | -0.31% | -1.00% | +2.96% | +0.21% | 1.53% | -0.34 |

No factor stress signals this week (all within ±2σ).

*Last updated: 2026-08-23 10:58 UTC*


---

## 3. Macro Signal Tracker

| Indicator | Current | 1W Change | Signal |
|-----------|---------|-----------|--------|
| HY Spread (OAS) | 275bps | +4bps | ⚠️ Widening |
| IG Spread (OAS) | 82bps | +3bps | ⚠️ Widening |
| 2s10s Yield Curve | 0.50% | -0.01% | Normal |
| 3M10Y Yield Curve | 0.86% | +0.04% | Normal |
| Fed Funds Rate | 3.63% | N/A | → |
| HY − IG Spread | 193bps | — | Risk sentiment proxy |

**Macro Summary:** Neutral macro backdrop

*Last updated: 2026-08-23 10:58 UTC*


---

## 4. Quant Research Digest

Three papers I found worth reading this week:

>**Dynamic Portfolio Optimization under CVaR Constraints**  — Anran Hu et al. | [arXiv](https://arxiv.org/abs/2608.20179v1)  

This paper studies continuous-time portfolio optimization with a CVaR constraint on terminal loss, showing optimal strategies exist without requiring complete markets. It provides useful mathematical duality results for dynamic risk-constrained setups in incomplete market formulations.

>**Entropic Value-at-Risk portfolio optimization for tempered stable Lévy processes** — Jaehyung Choi | [arXiv](https://arxiv.org/abs/2608.18022v1)  

The author develops an optimization framework using Entropic Value-at-Risk (EVaR) for returns following tempered stable Lévy processes. It works out analytical moment-generating function bounds to make coherent risk optimization tractable under heavy-tailed jump dynamics.

>**Multi-Level Market Making with Reinforcement Learning** — Patrick Cheridito et al. | [arXiv](https://arxiv.org/abs/2608.18195v1)  

This work frames limit order book market making as an RL problem that places orders across multiple price tiers while tracking inventory. It offers a practical formulation for modeling multi-level order placement dynamics beyond standard single-level analytical approximations.

*Last updated: 2026-08-23 10:58 UTC*


---

## 5. Stat of the Week

| Stat | Value | Context |
|------|-------|---------|
| CBOE Skew Index | 144 | Elevated tail risk (>130) |

The Skew Index sits at 144 while 20-day realized volatility is low at 13.2% and VIX is at 15.1. It shows a persistent spread where realized day-to-day index fluctuations are modest, but out-of-the-money option pricing remains elevated relative to historical norms.

*Last updated: 2026-08-23 10:58 UTC*


---

*Generated: 2026-08-23 10:58 UTC*