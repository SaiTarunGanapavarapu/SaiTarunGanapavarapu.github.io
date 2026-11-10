---
layout: post
title: "The Weekly Print"
date: 2026-11-06
categories: [quant, weekly]
excerpt: "Auto-generated weekly quant memo: market regime, factor performance, macro signals, and research digest for the week of November 6, 2026."

---

## 1. Market Regime Snapshot

**VIX Term Structure**

| Tenor | Level | vs. Spot |
|-------|-------|----------|
| VIX Spot | 25.6 | — |
| VIX 3M | 24.6 | -1.0 (Backwardation) |

**Realized vs. Implied Vol:** SPY 20D RV = 19.9%, VIX = 25.6. Spread = -5.7pp (realized vol below implied — calmer than feared).

**Cross-Asset Momentum (1-Month)**

| Asset | 1M Return | Signal |
|-------|-----------|--------|
| SPY (Equity) | -5.6% | 📉 Negative |
| TLT (Bonds) | +5.1% | 📈 Positive |
| GLD (Gold) | -3.1% | 📉 Negative |
| UUP (US Dollar) | +0.4% | 📈 Positive |

**Regime:** Mixed/transitional regime

*Last updated: 2026-11-09 22:32 UTC*


---

## 2. Factor Performance Dashboard

*Source: ETF Proxies (MTUM, VLUE, QUAL, USMV, IWM vs SPY)*

*Note: ETF proxy returns include market beta and are not directly comparable to factor-neutral French library returns.*

| Factor | Weekly | 1M | 3M | Mean (52W wkly) | Std (52W wkly) | Z |
|--------|--------|----|----|-----------------|----------------|---|
| Momentum 🚨 | -10.23% | -19.63% | -16.84% | +0.11% | 3.38% | -3.06 |
| Value 🚨 | -6.28% | -8.96% | -7.31% | +0.71% | 2.74% | -2.55 |
| Quality | -1.42% | -3.01% | -2.63% | +0.25% | 1.50% | -1.12 |
| Low Volatility | -1.65% | +1.21% | +0.73% | +0.20% | 1.24% | -1.49 |
| Size | +0.70% | +3.78% | -4.09% | +0.07% | 1.59% | +0.39 |

🚨 **Factor Stress:** Momentum (z=-3.06), Value (z=-2.55) — weekly return ≥ 2σ from trailing mean.

*Last updated: 2026-11-09 22:32 UTC*


---

## 3. Macro Signal Tracker

| Indicator | Current | 1W Change | Signal |
|-----------|---------|-----------|--------|
| HY Spread (OAS) | 342bps | -2bps | ✅ Tightening |
| IG Spread (OAS) | 93bps | -1bps | ✅ Tightening |
| 2s10s Yield Curve | 0.35% | -0.03% | Normal |
| 3M10Y Yield Curve | 0.67% | -0.11% | Normal |
| Fed Funds Rate | 3.88% | N/A | → |
| HY − IG Spread | 249bps | — | Risk sentiment proxy |

**Macro Summary:** Risk-on macro backdrop

*Last updated: 2026-11-09 22:32 UTC*


---

## 4. Quant Research Digest

Three papers I found worth reading this week:

>**Risk-Sensitive Reinforcement Learning for an Options Market Maker: An Empirical Study with Real S&P 500 Options** — Jacky Chen et al. | [arXiv](https://arxiv.org/abs/2611.10956v1)  

This paper trains a reinforcement learning agent on historical S&P 500 options data to see if it can beat standard delta hedging and heuristic rules for tail-risk protection. It's a great read if you are currently writing option pricing models and hedging simulators, as it highlights the practical frictions you have to code around when translating textbook Greeks into live order flow.

>**The Logic of Factor Portfolios: Boolean Rules, Interactions, and Trading Costs** — Ziyao Wang et al. | [arXiv](https://arxiv.org/abs/2611.09834v1)  

The authors formalize factor portfolio construction by treating threshold rules (like screening for high momentum) as pure Boolean logic to measure interaction effects and turnover. When writing a backtesting engine from scratch, adopting this kind of strict Boolean framework makes your C++ or Python codebase much cleaner and helps catch hidden trading costs before you even compile.

>**Is price-impact decay statistically identifiable by propagator estimation? Diffusive prices force the inferred kernel to be transient and fine-tuned** — Shunta Fujiwara et al. | [arXiv](https://arxiv.org/abs/2611.10574v1)  

This study dives into the "diffusivity puzzle" of market microstructure, showing how the mathematical kernels used to estimate price impact decay are inherently fine-tuned by diffusive prices. It is a fantastic mathematical reality check for anyone modeling limit order book dynamics, proving that some standard statistical estimations in microstructure literature are structurally forced rather than empirically discovered.

*Last updated: 2026-11-09 22:32 UTC*


---

## 5. Stat of the Week

| Stat | Value | Context |
|------|-------|---------|
| CBOE Skew Index | 154 | Elevated tail risk (>130) |

The VIX term structure just flipped into backwardation and the Skew Index is sitting at a lofty 154, all while the Momentum and Value factors are experiencing a massive 3-sigma crash on our dashboard. As I'm building out the volatility estimation modules in my trading repositories this week, this setup is a perfect live case study on why static covariance matrices break down: implied tails are screaming stress and cross-sectional factors are breaking correlations, meaning standard risk parity models will completely fail in this regime.

*Last updated: 2026-11-09 22:32 UTC*


---

*Generated: 2026-11-09 22:32 UTC*