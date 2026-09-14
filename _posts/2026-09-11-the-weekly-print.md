---
layout: post
title: "The Weekly Print"
date: 2026-09-11
categories: [quant, weekly]
excerpt: "Auto-generated weekly quant memo: market regime, factor performance, macro signals, and research digest for the week of September 11, 2026."

---

## 1. Market Regime Snapshot

**VIX Term Structure**

| Tenor | Level | vs. Spot |
|-------|-------|----------|
| VIX Spot | 15.8 | — |
| VIX 3M | 20.5 | +4.7 (Contango) |

**Realized vs. Implied Vol:** SPY 20D RV = 8.7%, VIX = 15.8. Spread = -7.1pp (realized vol below implied — calmer than feared).

**Cross-Asset Momentum (1-Month)**

| Asset | 1M Return | Signal |
|-------|-----------|--------|
| SPY (Equity) | -1.7% | 📉 Negative |
| TLT (Bonds) | -1.7% | 📉 Negative |
| GLD (Gold) | -0.0% | 📉 Negative |
| UUP (US Dollar) | -0.4% | 📉 Negative |

**Regime:** Mixed/transitional regime

*Last updated: 2026-09-13 21:55 UTC*


---

## 2. Factor Performance Dashboard

*Source: ETF Proxies (MTUM, VLUE, QUAL, USMV, IWM vs SPY)*

*Note: ETF proxy returns include market beta and are not directly comparable to factor-neutral French library returns.*

| Factor | Weekly | 1M | 3M | Mean (52W wkly) | Std (52W wkly) | Z |
|--------|--------|----|----|-----------------|----------------|---|
| Momentum | +2.54% | -2.44% | -3.65% | +0.41% | 2.80% | +0.76 |
| Value | -0.33% | +1.46% | +3.20% | +1.06% | 2.58% | -0.54 |
| Quality | -1.46% | -2.33% | +2.17% | +0.31% | 1.55% | -1.14 |
| Low Volatility | -2.16% | -1.15% | +4.48% | +0.15% | 1.18% | -1.95 |
| Size | -1.00% | -3.53% | -4.06% | +0.10% | 1.51% | -0.72 |

No factor stress signals this week (all within ±2σ).

*Last updated: 2026-09-13 21:55 UTC*


---

## 3. Macro Signal Tracker

| Indicator | Current | 1W Change | Signal |
|-----------|---------|-----------|--------|
| HY Spread (OAS) | 270bps | +5bps | ⚠️ Widening |
| IG Spread (OAS) | 80bps | -1bps | ✅ Tightening |
| 2s10s Yield Curve | 0.33% | -0.10% | Normal |
| 3M10Y Yield Curve | 0.89% | +0.01% | Normal |
| Fed Funds Rate | 3.63% | N/A | → |
| HY − IG Spread | 190bps | — | Risk sentiment proxy |

**Macro Summary:** Neutral macro backdrop

*Last updated: 2026-09-13 21:55 UTC*


---

## 4. Quant Research Digest

Three papers I found worth reading this week:

>**Exact calibration of structural models via time-change** — Argimiro Arratia et al. | [arXiv](https://arxiv.org/abs/2609.03552v1)  

This paper presents a method to exactly calibrate structural credit models to market survival curves by applying a deterministic time-change clock to a latent first-passage-time process. It demonstrates that models like AT1P can be mathematically formulated as a time-changed drifted Brownian motion, turning a complex calibration problem into a simple, fast function inversion.

>**Seasonal Trading in Commodity Futures: Evidence from Regression and Singular Spectrum Signals** — Ralph Kosch and  | [arXiv](https://arxiv.org/abs/2609.03218v1)  

This study evaluates calendar regressions against Singular Spectrum Analysis (SSA) to see if commodity futures seasonality actually survives transaction costs and out-of-sample rolling. It acts as a great reality check for backtesting, demonstrating that while flexible models can detect complex seasonal patterns, translating them into statistically robust outperformance over a simple long benchmark is incredibly difficult.

>**Optimized day trading via reinforcement learning and technical analysis using attention-LSTM, CNN, and explainable state modeling** — Muktinath Vishwakarma et al | [Paper](https://link.springer.com/article/10.1007/s13042-026-03298-9)  

The authors build an intraday Q-learning agent that fuses Attention-LSTMs and CNNs to capture temporal and spatial dependencies, and then uses K-means clustering to discretize those high-dimensional features into manageable states. It bridges the gap between deep representation learning and traditional reinforcement learning, offering a highly practical architecture for building adaptive trading pipelines without suffering from the curse of dimensionality.

*Last updated: 2026-09-13 21:55 UTC*


---

## 5. Stat of the Week

*Auto-computed candidates — pick one and add your commentary below.*

| Stat | Value | Context |
|------|-------|---------|
| CBOE Skew Index | 154 | Elevated tail risk (>130) |
| Momentum / Low Vol 20D correlation | -0.25 | No crowding signal (< 0.6) |

The Skew Index climbed to 154 this week, while the 20-day realized volatility for SPY stayed low at 8.7%. It is an interesting divergence where daily index returns are relatively flat, but out-of-the-money option pricing remains elevated. This is a good data point validating why we need to track tail-risk metrics separately from standard historical variance when evaluating market environments.

*Last updated: 2026-09-13 21:55 UTC*


---

*Generated: 2026-09-13 21:55 UTC*
