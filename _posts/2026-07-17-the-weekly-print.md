---
layout: post
title: "The Weekly Print"
date: 2026-07-17
categories: [quant, weekly]
excerpt: "Auto-generated weekly quant memo: market regime, factor performance, macro signals, and research digest for the week of July 17, 2026."

---

## 1. Market Regime Snapshot

**VIX Term Structure**

| Tenor | Level | vs. Spot |
|-------|-------|----------|
| VIX Spot | 18.8 | — |
| VIX 3M | 20.5 | +1.8 (Contango) |

**Realized vs. Implied Vol:** SPY 20D RV = 12.2%, VIX = 18.8. Spread = -6.5pp (realized vol below implied — calmer than feared).

**Cross-Asset Momentum (1-Month)**

| Asset | 1M Return | Signal |
|-------|-----------|--------|
| SPY (Equity) | +0.6% | 📈 Positive |
| TLT (Bonds) | -1.7% | 📉 Negative |
| GLD (Gold) | -5.2% | 📉 Negative |
| UUP (US Dollar) | +0.5% | 📈 Positive |

**Regime:** Mixed/transitional regime

*Last updated: 2026-07-19 17:42 UTC*


---

## 2. Factor Performance Dashboard

*Source: ETF Proxies (MTUM, VLUE, QUAL, USMV, IWM vs SPY)*

*Note: ETF proxy returns include market beta and are not directly comparable to factor-neutral French library returns.*

| Factor | Weekly | 1M | 3M | Mean (52W wkly) | Std (52W wkly) | Z |
|--------|--------|----|----|-----------------|----------------|---|
| Momentum 🚨 | -6.12% | -7.35% | +11.67% | +0.50% | 2.71% | -2.44 |
| Value | -3.08% | -4.69% | +21.59% | +1.04% | 2.56% | -1.61 |
| Quality | -0.83% | +0.05% | +6.82% | +0.36% | 1.55% | -0.76 |
| Low Volatility | -1.19% | +0.72% | +2.66% | +0.11% | 1.16% | -1.12 |
| Size | +0.89% | +1.31% | +2.86% | +0.23% | 1.57% | +0.42 |

🚨 **Factor Stress:** Momentum (z=-2.44) — weekly return ≥ 2σ from trailing mean.

*Last updated: 2026-07-19 17:42 UTC*


---

## 3. Macro Signal Tracker

| Indicator | Current | 1W Change | Signal |
|-----------|---------|-----------|--------|
| HY Spread (OAS) | 271bps | +1bps | ⚠️ Widening |
| IG Spread (OAS) | 78bps | +2bps | ⚠️ Widening |
| 2s10s Yield Curve | 0.37% | +0.02% | Normal |
| 3M10Y Yield Curve | 0.70% | -0.01% | Normal |
| Fed Funds Rate | 3.63% | N/A | → |
| HY − IG Spread | 193bps | — | Risk sentiment proxy |

**Macro Summary:** Neutral macro backdrop

*Last updated: 2026-07-19 17:42 UTC*


---

## 4. Quant Research Digest

Three papers I found worth reading this week:

>**SciPhy Reinforcement Learning for Portfolio Optimization** — Igor Halperin et al. | [arXiv](https://arxiv.org/abs/2607.15195v1)  

The authors formulate continuous-time portfolio optimization with explicit transaction costs using a physics-informed reinforcement learning framework. It's an interesting approach to embedding continuous state constraints directly into stochastic control policies for allocation problems.

>**Measuring Sentiment News with Transformer-Based Language Models** — Maria Saveria Mavillonio et al. | [arXiv](https://arxiv.org/abs/2607.13968v1)  

This paper benchmarks transformer-based daily news mood indices against standard dictionary word-count approaches. It highlights how contextual language models handle edge cases like negation and semantic nuance much better than rigid word-counting heuristics.

>**How Much of a 10-K Matters? Aggregation-Dependent Value of Full-Text versus Risk-Factor Sentiment** — Sanggyu Sean Choi | [arXiv](https://arxiv.org/abs/2607.14174v1)  

This study tests whether full 10-K text or specific Item 1A risk-factor disclosures provide a better predictive signal for volatility versus returns. It shows that targeting volatility directly with risk text yields cleaner results than using text simply to forecast equity direction.

*Last updated: 2026-07-19 17:42 UTC*


---

## 5. Stat of the Week

| Stat | Value | Context |
|------|-------|---------|
| CBOE Skew Index | 147 | Elevated tail risk (>130) |

Momentum was the main outlier on the dashboard this week, dropping over 6% (-2.44 z-score). Meanwhile, the Skew Index rose back to 147 even as 20-day realized volatility stayed low at 12.2%. It’s a clean example of market divergence: headline index volatility looks calm, but factor-level drawdowns and option pricing point to lingering left-tail risk.

*Last updated: 2026-07-19 17:42 UTC*


---

*Generated: 2026-07-19 17:42 UTC*