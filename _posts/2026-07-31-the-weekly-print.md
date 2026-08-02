---
layout: post
title: "The Weekly Print"
date: 2026-07-31
categories: [quant, weekly]
excerpt: "Auto-generated weekly quant memo: market regime, factor performance, macro signals, and research digest for the week of July 31, 2026."

---

## 1. Market Regime Snapshot

**VIX Term Structure**

| Tenor | Level | vs. Spot |
|-------|-------|----------|
| VIX Spot | 16.0 | — |
| VIX 3M | 20.5 | +4.6 (Contango) |

**Realized vs. Implied Vol:** SPY 20D RV = 12.7%, VIX = 16.0. Spread = -3.3pp (realized vol below implied — calmer than feared).

**Cross-Asset Momentum (1-Month)**

| Asset | 1M Return | Signal |
|-------|-----------|--------|
| SPY (Equity) | +0.3% | 📈 Positive |
| TLT (Bonds) | -3.8% | 📉 Negative |
| GLD (Gold) | -1.7% | 📉 Negative |
| UUP (US Dollar) | -0.6% | 📉 Negative |

**Regime:** Mixed/transitional regime

*Last updated: 2026-08-02 17:13 UTC*


---

## 2. Factor Performance Dashboard

*Source: ETF Proxies (MTUM, VLUE, QUAL, USMV, IWM vs SPY)*

*Note: ETF proxy returns include market beta and are not directly comparable to factor-neutral French library returns.*

| Factor | Weekly | 1M | 3M | Mean (52W wkly) | Std (52W wkly) | Z |
|--------|--------|----|----|-----------------|----------------|---|
| Momentum | -2.22% | -8.69% | +5.61% | +0.46% | 2.74% | -0.98 |
| Value | -1.80% | -2.22% | +14.81% | +1.04% | 2.56% | -1.11 |
| Quality | +1.16% | +0.21% | +6.01% | +0.35% | 1.53% | +0.53 |
| Low Volatility | +1.01% | +1.07% | +3.80% | +0.13% | 1.13% | +0.78 |
| Size | -1.09% | -2.90% | +0.78% | +0.23% | 1.56% | -0.84 |

No factor stress signals this week (all within ±2σ).

*Last updated: 2026-08-02 17:13 UTC*


---

## 3. Macro Signal Tracker

| Indicator | Current | 1W Change | Signal |
|-----------|---------|-----------|--------|
| HY Spread (OAS) | 284bps | +7bps | ⚠️ Widening |
| IG Spread (OAS) | 80bps | +1bps | ⚠️ Widening |
| 2s10s Yield Curve | 0.47% | +0.11% | Normal |
| 3M10Y Yield Curve | 0.92% | +0.19% | Normal |
| Fed Funds Rate | 3.63% | N/A | → |
| HY − IG Spread | 204bps | — | Risk sentiment proxy |

**Macro Summary:** Neutral macro backdrop

*Last updated: 2026-08-02 17:13 UTC*


---

## 4. Quant Research Digest

Three papers I found worth reading this week:

>**Train Often, Deploy Selectively: Forward-Gated Model Replacement in Crypto Markets** — Aditya Dutta | [arXiv](https://arxiv.org/abs/2607.28577v1)  

This paper outlines a deployment policy where a challenger forecasting model is evaluated off the serving path against delayed labels before replacing an incumbent. It highlights a critical MLOps reality: continuous retraining does not automatically yield out-of-sample improvements over a stable baseline.

>**Optimal Execution with Passive Market Impact** — Alexander Barzykin et al. | [arXiv](https://arxiv.org/abs/2607.28323v1)  

The authors derive an execution model using limit orders based on empirical fill probabilities and the linear response of price changes to order flow imbalance. It is a highly grounded approach to microstructure modeling that relies on observable limit order book mechanics rather than purely theoretical assumptions.

>**FinSMART: Financial Sentiment Analysis for Algorithmic Trading through Market-Aligned Reinforcement Learning** — Giorgos Iacovides et al. | [arXiv](https://arxiv.org/abs/2607.28127v1)  

This research moves beyond static, supervised training for LLMs in sentiment analysis by using reinforcement learning to align models directly with dynamic market conditions. It marks an important structural shift from static dictionary-based sentiment scoring toward adaptive models that evolve with new financial data.

*Last updated: 2026-08-02 17:13 UTC*


---

## 5. Stat of the Week

| Stat | Value | Context |
|------|-------|---------|
| CBOE Skew Index | 141 | Elevated tail risk (>130) |

The Skew Index remains elevated at 141, while 20-day realized volatility sits low at 12.7% and the VIX is at 16.0. This continued divergence mathematically indicates that while daily index movements are subdued, the options market is persistently pricing in left-tail risk. It is a clear observation that standard mean-variance metrics, which rely heavily on average volatility, are currently obscuring the true tail behavior of the distribution.

*Last updated: 2026-08-02 17:13 UTC*


---

*Generated: 2026-08-02 17:13 UTC*