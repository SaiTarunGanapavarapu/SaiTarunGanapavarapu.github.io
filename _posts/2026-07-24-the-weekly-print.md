---
layout: post
title: "The Weekly Print"
date: 2026-07-24
categories: [quant, weekly]
excerpt: "Auto-generated weekly quant memo: market regime, factor performance, macro signals, and research digest for the week of July 24, 2026."

---

## 1. Market Regime Snapshot

**VIX Term Structure**

| Tenor | Level | vs. Spot |
|-------|-------|----------|
| VIX Spot | 18.6 | — |
| VIX 3M | 20.5 | +2.0 (Contango) |

**Realized vs. Implied Vol:** SPY 20D RV = 11.7%, VIX = 18.6. Spread = -6.9pp (realized vol below implied — calmer than feared).

**Cross-Asset Momentum (1-Month)**

| Asset | 1M Return | Signal |
|-------|-----------|--------|
| SPY (Equity) | +0.6% | 📈 Positive |
| TLT (Bonds) | -4.3% | 📉 Negative |
| GLD (Gold) | +0.7% | 📈 Positive |
| UUP (US Dollar) | +0.4% | 📈 Positive |

**Regime:** Mixed/transitional regime

*Last updated: 2026-07-25 11:02 UTC*


---

## 2. Factor Performance Dashboard

*Source: ETF Proxies (MTUM, VLUE, QUAL, USMV, IWM vs SPY)*

*Note: ETF proxy returns include market beta and are not directly comparable to factor-neutral French library returns.*

| Factor | Weekly | 1M | 3M | Mean (52W wkly) | Std (52W wkly) | Z |
|--------|--------|----|----|-----------------|----------------|---|
| Momentum | +1.42% | -6.71% | +11.18% | +0.51% | 2.72% | +0.34 |
| Value | +2.79% | -1.02% | +22.15% | +1.04% | 2.58% | +0.68 |
| Quality | -0.49% | +1.70% | +5.49% | +0.32% | 1.55% | -0.52 |
| Low Volatility | +0.36% | +2.20% | +3.12% | +0.09% | 1.15% | +0.23 |
| Size | -0.39% | -2.66% | +1.34% | +0.20% | 1.58% | -0.38 |

No factor stress signals this week (all within ±2σ).

*Last updated: 2026-07-25 11:02 UTC*


---

## 3. Macro Signal Tracker

| Indicator | Current | 1W Change | Signal |
|-----------|---------|-----------|--------|
| HY Spread (OAS) | 277bps | +6bps | ⚠️ Widening |
| IG Spread (OAS) | 79bps | +1bps | ⚠️ Widening |
| 2s10s Yield Curve | 0.36% | -0.01% | Normal |
| 3M10Y Yield Curve | 0.73% | +0.03% | Normal |
| Fed Funds Rate | 3.63% | N/A | → |
| HY − IG Spread | 198bps | — | Risk sentiment proxy |

**Macro Summary:** Neutral macro backdrop

*Last updated: 2026-07-25 11:02 UTC*


---

## 4. Quant Research Digest

Three papers I found worth reading this week:

>**Retail Trader's Ruin: An Anatomy of Popular Signal Failure** — Adam Darmanin | [arXiv](https://arxiv.org/abs/2607.20093v1)  

This paper systematically evaluates common retail trading signals against strict statistical and economic filters. It demonstrates that raw statistical edges in backtests frequently vanish when fully accounting for trading costs, leverage survival, and multiplicity corrections.

>**Quantum Kernels and the Cross-Section of Stock Returns: Anatomy of a Vanishing Advantage** — Junchi Shen | [arXiv](https://arxiv.org/abs/2607.20168v1)  

This study runs a controlled empirical test comparing classical and quantum kernels for cross-sectional return prediction and finds no distinct quantum advantage. It emphasizes the methodological importance of establishing equal-budget classical baselines before assessing the viability of more complex algorithmic approaches.

>**Quantifying Sub-Optimality in Routing for Automated Market Makers** — Weiye Xi et al. | [arXiv](https://arxiv.org/abs/2607.20762v1)  

The authors audit millions of Ethereum swaps to calculate the financial value lost due to suboptimal DEX routing. It provides a direct quantification of the real-world friction and slippage caused by inefficient execution logic in decentralized order routing.

*Last updated: 2026-07-25 11:02 UTC*


---

## 5. Stat of the Week

| Stat | Value | Context |
|------|-------|---------|
| CBOE Skew Index | 147 | Elevated tail risk (>130) |

The Skew Index remains elevated at 147 while SPY 20-day realized volatility has dropped below 12%. This divergence highlights a market environment where day-to-day fluctuations are minimal, but options markets are actively pricing in left-tail risk. It provides a clear empirical case for employing tail-risk constraints like CVaR rather than standard mean-variance optimization, which assumes normally distributed returns.

*Last updated: 2026-07-25 11:02 UTC*


---

*Generated: 2026-07-25 11:02 UTC*