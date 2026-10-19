---
layout: post
title: "The Weekly Print"
date: 2026-10-16
categories: [quant, weekly]
excerpt: "Auto-generated weekly quant memo: market regime, factor performance, macro signals, and research digest for the week of October 16, 2026."

---

## 1. Market Regime Snapshot

**VIX Term Structure**

| Tenor | Level | vs. Spot |
|-------|-------|----------|
| VIX Spot | 20.0 | — |
| VIX 3M | 20.5 | +0.5 (Contango) |

**Realized vs. Implied Vol:** SPY 20D RV = 10.5%, VIX = 20.0. Spread = -9.5pp (realized vol below implied — calmer than feared).

**Cross-Asset Momentum (1-Month)**

| Asset | 1M Return | Signal |
|-------|-----------|--------|
| SPY (Equity) | +0.2% | 📈 Positive |
| TLT (Bonds) | -1.1% | 📉 Negative |
| GLD (Gold) | -4.8% | 📉 Negative |
| UUP (US Dollar) | +1.9% | 📈 Positive |

**Regime:** Mixed/transitional regime

*Last updated: 2026-10-18 20:05 UTC*


---

## 2. Factor Performance Dashboard

*Source: ETF Proxies (MTUM, VLUE, QUAL, USMV, IWM vs SPY)*

*Note: ETF proxy returns include market beta and are not directly comparable to factor-neutral French library returns.*

| Factor | Weekly | 1M | 3M | Mean (52W wkly) | Std (52W wkly) | Z |
|--------|--------|----|----|-----------------|----------------|---|
| Momentum 🚨 | -8.38% | -4.23% | -2.93% | +0.32% | 3.06% | -2.85 |
| Value | -3.64% | -3.98% | +2.22% | +0.86% | 2.58% | -1.74 |
| Quality | -0.96% | +2.73% | +3.91% | +0.31% | 1.50% | -0.85 |
| Low Volatility | +0.73% | +2.45% | +5.28% | +0.17% | 1.22% | +0.46 |
| Size | -1.08% | -5.56% | -10.04% | -0.10% | 1.60% | -0.61 |

🚨 **Factor Stress:** Momentum (z=-2.85) — weekly return ≥ 2σ from trailing mean.

*Last updated: 2026-10-18 20:05 UTC*


---

## 3. Macro Signal Tracker

| Indicator | Current | 1W Change | Signal |
|-----------|---------|-----------|--------|
| HY Spread (OAS) | 323bps | +8bps | ⚠️ Widening |
| IG Spread (OAS) | 84bps | +2bps | ⚠️ Widening |
| 2s10s Yield Curve | 0.35% | -0.12% | Normal |
| 3M10Y Yield Curve | 0.83% | -0.16% | Normal |
| Fed Funds Rate | 3.75% | N/A | → |
| HY − IG Spread | 239bps | — | Risk sentiment proxy |

**Macro Summary:** Neutral macro backdrop

*Last updated: 2026-10-18 20:05 UTC*


---

## 4. Quant Research Digest

Three papers I found worth reading this week:

>**EvoQuantLab: Training-Free Dual-Loop Evolution for Auditable Quantitative Research** — Haolin Yang et al. | [arXiv](https://arxiv.org/abs/2610.17130)  

This framework integrates genetic programming with large language models to automate the discovery of alpha factors. The dual-loop methodology mitigates severe backtest overfitting common in agent-based approaches, yielding robust factor discovery across daily equities and high-turnover cryptocurrency data.

>**Ranking Prior Alignment for Credit Risk Modeling: When Do External Priors Matter?** — Qiye Lu et al. | [arXiv](https://arxiv.org/abs/2610.11146)  

The authors present a model-agnostic approach that incorporates ranking priors from domain experts or teacher models into credit scoring systems via KL divergence. This alignment technique improves cold-start performance in environments with scarce labeled data and remains beneficial even when the external priors contain moderate noise.

>**Trading Strategy Optimization via Textual Gradient** — Chaoqun Yang et al. | [arXiv](https://arxiv.org/abs/2610.03128)  

This system utilizes large language models to iteratively refine trading logic by evaluating backtest metrics and applying a Cross-Period Robust Objective (CPRO). It addresses the myopia of standard optimization routines by explicitly evaluating and retaining strategies that perform well across multiple shifting market regimes rather than isolated favorable periods.

*Last updated: 2026-10-18 20:05 UTC*


---

## 5. Stat of the Week

*Auto-computed candidates — pick one and add your commentary below.*

| Stat | Value | Context |
|------|-------|---------|
| CBOE Skew Index | 169 | Elevated tail risk (>130) |
| Momentum / Low Vol 20D correlation | 0.29 | No crowding signal (< 0.6) |

The CBOE Skew Index hit an extreme 169 this week, while the VIX spot pushed up to 20.0. Meanwhile, the 20-day realized volatility on the SPY remains subdued at just 10.5%. This massive 9.5 percentage point spread between implied and realized volatility, paired with a historically elevated skew, is an interesting structural divergence. It indicates that while the day-to-day index fluctuations are modest, the mechanical cost of out-of-the-money downside protection is commanding a steep premium.

*Last updated: 2026-10-18 20:05 UTC*


---

*Generated: 2026-10-18 20:05 UTC*
