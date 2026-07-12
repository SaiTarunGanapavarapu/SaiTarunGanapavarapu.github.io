---
layout: post
title: "The Weekly Print"
date: 2026-07-10
categories: [quant, weekly]
excerpt: "Auto-generated weekly quant memo: market regime, factor performance, macro signals, and research digest for the week of July 10, 2026."

---

## 1. Market Regime Snapshot

**VIX Term Structure**

| Tenor | Level | vs. Spot |
|-------|-------|----------|
| VIX Spot | 15.0 | — |
| VIX 3M | 18.6 | +3.5 (Contango) |

**Realized vs. Implied Vol:** SPY 20D RV = 14.8%, VIX = 15.0. Spread = -0.3pp (realized vol below implied — calmer than feared).

**Cross-Asset Momentum (1-Month)**

| Asset | 1M Return | Signal |
|-------|-----------|--------|
| SPY (Equity) | +4.3% | 📈 Positive |
| TLT (Bonds) | -0.1% | 📉 Negative |
| GLD (Gold) | +0.6% | 📈 Positive |
| UUP (US Dollar) | +1.2% | 📈 Positive |

**Regime:** Mixed/transitional regime

*Last updated: 2026-07-12 10:27 UTC*


---

## 2. Factor Performance Dashboard

*Source: ETF Proxies (MTUM, VLUE, QUAL, USMV, IWM vs SPY)*

*Note: ETF proxy returns include market beta and are not directly comparable to factor-neutral French library returns.*

| Factor | Weekly | 1M | 3M | Mean (52W wkly) | Std (52W wkly) | Z |
|--------|--------|----|----|-----------------|----------------|---|
| Momentum | +1.66% | +3.37% | +22.76% | +0.62% | 2.56% | +0.41 |
| Value | +1.24% | +0.64% | +28.29% | +1.07% | 2.51% | +0.07 |
| Quality | +0.58% | +2.78% | +9.90% | +0.35% | 1.55% | +0.14 |
| Low Volatility | -0.13% | +2.60% | +4.48% | +0.11% | 1.16% | -0.21 |
| Size | -1.87% | +1.32% | +1.80% | +0.19% | 1.57% | -1.31 |

No factor stress signals this week (all within ±2σ).

*Last updated: 2026-07-12 10:27 UTC*


---

## 3. Macro Signal Tracker

| Indicator | Current | 1W Change | Signal |
|-----------|---------|-----------|--------|
| HY Spread (OAS) | 270bps | -5bps | ✅ Tightening |
| IG Spread (OAS) | 76bps | +1bps | ⚠️ Widening |
| 2s10s Yield Curve | 0.35% | +0.00% | Normal |
| 3M10Y Yield Curve | 0.71% | +0.04% | Normal |
| Fed Funds Rate | 3.63% | N/A | → |
| HY − IG Spread | 194bps | — | Risk sentiment proxy |

**Macro Summary:** Risk-on macro backdrop

*Last updated: 2026-07-12 10:27 UTC*


---

## 4. Quant Research Digest

Three papers I found worth reading this week:

>**Estimating the Stochastic Discount Factor from Option Prices and Predicting the Equity Premium** — Kenichiro Shiraya et al. | [arXiv](https://arxiv.org/abs/2607.08500v1)  

The authors use S&P 500 option data to isolate a stable, time-varying volatility scaled Stochastic Discount Factor (SDF) that smooths out observation noise. It is a really clean mathematical approach to recovering forward-looking expectations without letting empirical market noise mess up the core asset pricing signal.

>**Iterative detection of global factors near the BBP phase transition** — Andrés García-Medina | [arXiv](https://arxiv.org/abs/2607.06908v1)  

This paper deals with the classic issue of signal-to-noise separation in high-dimensional correlation matrices when you have limited data observations. It offers a solid random matrix theory perspective on trying to spot weak global factors right near the Marčenko–Pastur spectral edge where they usually get hidden by random noise.

>**tsbootstrap: Distribution-Free Uncertainty Quantification and Conformal Prediction for Time Series** — Sankalp Gilda | [arXiv](https://arxiv.org/abs/2607.06690v1)  

This introduces an open-source library that combines time-series resampling methods (like block and sieve bootstrapping) with adaptive conformal prediction. It is a highly practical coding resource for anyone trying to build distribution-free confidence intervals for non-stationary, dependent data streams.

*Last updated: 2026-07-12 10:27 UTC*


---

## 5. Stat of the Week

| Stat | Value | Context |
|------|-------|---------|
| CBOE Skew Index | 144 | Elevated tail risk (>130) |

The Skew Index is still lingering up around 144, but the VIX dropped down to 15.0 and the 20-day realized volatility is sitting calm at 14.8%. We are looking at a classic data divergence where day-to-day fluctuations look totally flat, but out-of-the-money options pricing reveals that people are still paying a hefty premium to cover against a severe market drop. It is a good example of why looking at a single average volatility metric can result in completely missing the actual tail behavior of the distribution.

*Last updated: 2026-07-12 10:27 UTC*


---

*Generated: 2026-07-12 10:27 UTC*