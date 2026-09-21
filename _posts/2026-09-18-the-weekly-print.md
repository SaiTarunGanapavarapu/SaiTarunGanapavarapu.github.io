---
layout: post
title: "The Weekly Print"
date: 2026-09-18
categories: [quant, weekly]
excerpt: "Auto-generated weekly quant memo: market regime, factor performance, macro signals, and research digest for the week of September 18, 2026."

---

## 1. Market Regime Snapshot

**VIX Term Structure**

| Tenor | Level | vs. Spot |
|-------|-------|----------|
| VIX Spot | 14.8 | — |
| VIX 3M | 18.2 | +3.4 (Contango) |

**Realized vs. Implied Vol:** SPY 20D RV = 9.2%, VIX = 14.8. Spread = -5.6pp (realized vol below implied — calmer than feared).

**Cross-Asset Momentum (1-Month)**

| Asset | 1M Return | Signal |
|-------|-----------|--------|
| SPY (Equity) | +0.1% | 📈 Positive |
| TLT (Bonds) | -0.9% | 📉 Negative |
| GLD (Gold) | -3.4% | 📉 Negative |
| UUP (US Dollar) | +1.7% | 📈 Positive |

**Regime:** Mixed/transitional regime

*Last updated: 2026-09-21 11:29 UTC*


---

## 2. Factor Performance Dashboard

*Source: ETF Proxies (MTUM, VLUE, QUAL, USMV, IWM vs SPY)*

*Note: ETF proxy returns include market beta and are not directly comparable to factor-neutral French library returns.*

| Factor | Weekly | 1M | 3M | Mean (52W wkly) | Std (52W wkly) | Z |
|--------|--------|----|----|-----------------|----------------|---|
| Momentum | +1.04% | +1.43% | -8.35% | +0.43% | 2.80% | +0.22 |
| Value | -1.17% | -0.10% | +0.45% | +1.01% | 2.60% | -0.84 |
| Quality | -0.25% | -2.09% | +1.74% | +0.29% | 1.55% | -0.35 |
| Low Volatility | -0.90% | -2.54% | +4.75% | +0.13% | 1.19% | -0.86 |
| Size | -1.32% | -4.92% | -5.82% | +0.07% | 1.52% | -0.91 |

No factor stress signals this week (all within ±2σ).

*Last updated: 2026-09-21 11:29 UTC*


---

## 3. Macro Signal Tracker

| Indicator | Current | 1W Change | Signal |
|-----------|---------|-----------|--------|
| HY Spread (OAS) | 268bps | +3bps | ⚠️ Widening |
| IG Spread (OAS) | 77bps | -3bps | ✅ Tightening |
| 2s10s Yield Curve | 0.25% | -0.08% | Flat |
| 3M10Y Yield Curve | 0.87% | -0.02% | Normal |
| Fed Funds Rate | 3.63% | N/A | → |
| HY − IG Spread | 191bps | — | Risk sentiment proxy |

**Macro Summary:** Neutral macro backdrop

*Last updated: 2026-09-21 11:29 UTC*


---

## 4. Quant Research Digest

Three papers I found worth reading this week:

>**Nested Clustered Optimization Is One End of a Schur Bridge, and the Interior Is Sometimes Provably Better** — Peter Cotton | [Link](https://arxiv.org/abs/2609.21271v1)  

This paper connects hierarchical/clustered portfolio allocation to standard minimum-variance optimization by showing how block-inversion Schur complements link the two approaches. It gives clean linear algebra intuition for why and when interpolating between pure cluster-block weights and full-covariance inversion yields lower out-of-sample risk.

>**Adapting the Actor Model of Concurrency for High-Frequency Trading: Synchronous Message Delivery (fast_send) and a Tick-to-Book Latency Study**  — Vincent Maciejewski | [Link](https://arxiv.org/abs/2609.21173v1)  

The author shows how co-located actors can eliminate thread context switches and heap-allocated mailboxes using a C++20 synchronous delivery primitive (`fast_send`). It is a very practical systems paper for execution pipelines, proving you can retain clean, isolated concurrency semantics without paying the typical microsecond latency penalty.

>**Principal component error in high-dimensional factor models** — Alex Bernstein et al. | [Link](https://arxiv.org/abs/2609.20550v1)  

This work derives asymptotic error limits for sample covariance eigenvectors when the number of assets grows relative to a bounded sample length. It provides an explicit mathematical reminder of how much eigenvector noise contaminates statistical factor models, which is directly relevant when using PCA for dimension reduction or risk decomposition.

*Last updated: 2026-09-21 11:29 UTC*


---

## 5. Stat of the Week

| Stat | Value | Context |
|------|-------|---------|
| CBOE Skew Index | 148 | Elevated tail risk (>130) |

The Skew Index sits at 148 while 20-day realized volatility on SPY remains subdued at 9.2% and VIX spot trades at 14.8. It is the same quiet tape we have seen over the past several weeks: realized day-to-day index fluctuations are modest, yet out-of-the-money put pricing stays high. It is a helpful check against relying purely on rolling standard deviations to gauge whether options markets view downside risk as symmetric.

*Last updated: 2026-09-21 11:29 UTC*


---

*Generated: 2026-09-21 11:29 UTC*