---
layout: post
title: "The Weekly Print"
date: 2026-09-04
categories: [quant, weekly]
excerpt: "Auto-generated weekly quant memo: market regime, factor performance, macro signals, and research digest for the week of September 4, 2026."

---

## 1. Market Regime Snapshot

**VIX Term Structure**

| Tenor | Level | vs. Spot |
|-------|-------|----------|
| VIX Spot | 14.5 | — |
| VIX 3M | 20.5 | +6.0 (Contango) |

**Realized vs. Implied Vol:** SPY 20D RV = 8.1%, VIX = 14.5. Spread = -6.4pp (realized vol below implied — calmer than feared).

**Cross-Asset Momentum (1-Month)**

| Asset | 1M Return | Signal |
|-------|-----------|--------|
| SPY (Equity) | -0.4% | 📉 Negative |
| TLT (Bonds) | -0.3% | 📉 Negative |
| GLD (Gold) | +2.1% | 📈 Positive |
| UUP (US Dollar) | +0.0% | 📈 Positive |

**Regime:** Mixed/transitional regime

*Last updated: 2026-09-06 20:27 UTC*


---

## 2. Factor Performance Dashboard

*Source: ETF Proxies (MTUM, VLUE, QUAL, USMV, IWM vs SPY)*

*Note: ETF proxy returns include market beta and are not directly comparable to factor-neutral French library returns.*

| Factor | Weekly | 1M | 3M | Mean (52W wkly) | Std (52W wkly) | Z |
|--------|--------|----|----|-----------------|----------------|---|
| Momentum | +1.72% | -1.07% | -0.42% | +0.47% | 2.84% | +0.44 |
| Value | +2.10% | +4.75% | +7.46% | +1.09% | 2.56% | +0.39 |
| Quality | -0.47% | -1.06% | +4.62% | +0.33% | 1.54% | -0.51 |
| Low Volatility | -0.92% | +0.80% | +5.73% | +0.16% | 1.17% | -0.93 |
| Size | -0.02% | -0.95% | +0.57% | +0.12% | 1.50% | -0.09 |

No factor stress signals this week (all within ±2σ).

*Last updated: 2026-09-06 20:27 UTC*


---

## 3. Macro Signal Tracker

| Indicator | Current | 1W Change | Signal |
|-----------|---------|-----------|--------|
| HY Spread (OAS) | 265bps | +2bps | ⚠️ Widening |
| IG Spread (OAS) | 81bps | +2bps | ⚠️ Widening |
| 2s10s Yield Curve | 0.41% | +0.02% | Normal |
| 3M10Y Yield Curve | 0.87% | +0.04% | Normal |
| Fed Funds Rate | 3.63% | N/A | → |
| HY − IG Spread | 184bps | — | Risk sentiment proxy |

**Macro Summary:** Neutral macro backdrop

*Last updated: 2026-09-06 20:27 UTC*


---

## 4. Quant Research Digest

Three papers I found worth reading this week:

>**An Entropic Factor Model for Robust Portfolio Replication** — Argimiro Arratia et al. | [arXiv](https://arxiv.org/abs/2609.03552v1)  

The authors frame sparse portfolio replication as an ill-posed inverse problem and use an entropic factor approach to regularize it. It offers a practical formulation to avoid the unstable weights and over-leverage that often appear when using simple variance minimization on asset subsets.

>**The Analyst in the Prompt: Role, Retrieval, and Memory Biases in LLM Financial Analysis** — Ahmed Asaad et al. | [arXiv](https://arxiv.org/abs/2609.03218v1)  

This paper tests how user context, role prompts, and memory mechanisms systematically shift LLM conclusions when evaluating the exact same underlying financial evidence. It is a useful reminder of how prompting and context layers can inadvertently inject bias into automated research workflows.

>**Modeling Trade Durations under Temporal Granularity Effects in Forex Markets** — Vladimír Holý | [arXiv](https://arxiv.org/abs/2609.02660v1)  

The author proposes an adjusted ACD model to handle the clustering of trade timestamps around integer second marks in high-frequency FX data. It directly addresses an empirical artifact in tick data that standard continuous duration models tend to miss.

*Last updated: 2026-09-06 20:27 UTC*


---

## 5. Stat of the Week

| Stat | Value | Context |
|------|-------|---------|
| CBOE Skew Index | 152 | Elevated tail risk (>130) |

The Skew Index reached 152 this week while 20-day realized volatility on SPY dropped down to 8.1% and VIX spot hovered at 14.5. It is an interesting spread in the data: realized day-to-day index movement is quite flat, but out-of-the-money put pricing remains elevated relative to median levels.

*Last updated: 2026-09-06 20:27 UTC*


---

*Generated: 2026-09-06 20:27 UTC*