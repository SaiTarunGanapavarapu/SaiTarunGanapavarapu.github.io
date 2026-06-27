---
layout: post
title: "The Weekly Print"
date: 2026-06-26
categories: [quant, weekly]
excerpt: "Auto-generated weekly quant memo: market regime, factor performance, macro signals, and research digest for the week of June 26, 2026."

---

## 1. Market Regime Snapshot

**VIX Term Structure**

| Tenor | Level | vs. Spot |
|-------|-------|----------|
| VIX Spot | 18.4 | — |
| VIX 3M | 19.6 | +1.2 (Contango) |

**Realized vs. Implied Vol:** SPY 20D RV = 16.9%, VIX = 18.4. Spread = -1.5pp (realized vol below implied — calmer than feared).

**Cross-Asset Momentum (1-Month)**

| Asset | 1M Return | Signal |
|-------|-----------|--------|
| SPY (Equity) | -3.1% | 📉 Negative |
| TLT (Bonds) | +2.3% | 📈 Positive |
| GLD (Gold) | -9.5% | 📉 Negative |
| UUP (US Dollar) | +2.7% | 📈 Positive |

**Regime:** Mixed/transitional regime

*Last updated: 2026-06-27 13:49 UTC*


---

## 2. Factor Performance Dashboard

*Source: Ken French Data Library (Low Volatility: USMV ETF proxy)*

*Note: ETF proxy returns include market beta and are not directly comparable to factor-neutral French library returns.*

| Factor | Weekly | 1M | 3M | Mean (52W wkly) | Std (52W wkly) | Z |
|--------|--------|----|----|-----------------|----------------|---|
| Momentum | +2.22% | +10.73% | +12.98% | +0.39% | 2.07% | +0.89 |
| Value | +1.04% | -1.26% | +5.07% | +0.24% | 1.66% | +0.48 |
| Quality | -1.27% | -3.90% | -2.95% | -0.27% | 1.21% | -0.83 |
| Low Volatility | +0.35% | +2.05% | +0.37% | +0.08% | 1.11% | +0.24 |
| Size | -0.94% | +0.44% | +1.51% | +0.15% | 1.27% | -0.86 |

No factor stress signals this week (all within ±2σ).

*Last updated: 2026-06-27 13:49 UTC*


---

## 3. Macro Signal Tracker

| Indicator | Current | 1W Change | Signal |
|-----------|---------|-----------|--------|
| HY Spread (OAS) | 278bps | +12bps | ⚠️ Widening |
| IG Spread (OAS) | 76bps | +2bps | ⚠️ Widening |
| 2s10s Yield Curve | 0.31% | +0.04% | Normal |
| 3M10Y Yield Curve | 0.55% | -0.08% | Normal |
| Fed Funds Rate | 3.63% | N/A | → |
| HY − IG Spread | 202bps | — | Risk sentiment proxy |

**Macro Summary:** Neutral macro backdrop

*Last updated: 2026-06-27 13:49 UTC*


---

## 4. Quant Research Digest

Three papers I found worth reading this week:

>**Pretrained Time-Series Foundation Models for Financial Return Forecasting** — Miquel Noguer I Alonso, Rodolfo Pereira Franklin | [arXiv](https://arxiv.org/abs/2606.27100v1)  

This paper evaluates whether pretrained time-series foundation models can outperform standard neural baselines when faced with the low signal-to-noise ratios inherent to financial returns. It is a necessary benchmark for assessing if massive structural pretraining actually provides an edge in noisy, non-stationary market environments.

>**Portfolio Optimization for Commodity ETFs under Heavy-Tailed Returns** — Nicholas Appiah et al | [arXiv](https://arxiv.org/abs/2606.26625v1)  

This research investigates asset allocation techniques across commodity ETFs by explicitly modeling their heavy-tailed return behaviors. Providing a framework that properly handles non-normal distributions is critical for robust optimization, especially in fundamentally volatile sectors like energy and metals.

>**Data-Driven Duration Management -- Term Structure Forecasting Using Machine Learning** — Tobias Lausser et al. | [arXiv](https://arxiv.org/abs/2606.26815v1)  

By comparing traditional econometric models against machine learning approaches for term structure forecasting, this paper explores the trade-offs in yield curve prediction. It offers a practical methodological comparison for evaluating the efficacy of ML in fixed-income duration management pipelines.

*Last updated: 2026-06-27 13:49 UTC*


---

## 5. Stat of the Week

| Stat | Value | Context |
|------|-------|---------|
| CBOE Skew Index | 139 | Elevated tail risk (>130) |

The Skew Index is still high at 139, while the VIX (18.4) and actual market volatility (16.9%) are pretty low. This means day-to-day trading is quiet, but people are still paying a premium for insurance against a big crash. It's a good example of why looking at average volatility alone doesn't tell the whole story, and why tracking extreme tail risk matters.

*Last updated: 2026-06-27 13:49 UTC*


---

*Generated: 2026-06-27 13:49 UTC*
