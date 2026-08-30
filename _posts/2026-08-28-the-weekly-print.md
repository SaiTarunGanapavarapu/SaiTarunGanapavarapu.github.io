---
layout: post
title: "The Weekly Print"
date: 2026-08-28
categories: [quant, weekly]
excerpt: "Auto-generated weekly quant memo: market regime, factor performance, macro signals, and research digest for the week of August 28, 2026."

---

## 1. Market Regime Snapshot

**VIX Term Structure**

| Tenor | Level | vs. Spot |
|-------|-------|----------|
| VIX Spot | 14.4 | — |
| VIX 3M | 17.5 | +3.0 (Contango) |

**Realized vs. Implied Vol:** SPY 20D RV = 10.4%, VIX = 14.4. Spread = -4.0pp (realized vol below implied — calmer than feared).

**Cross-Asset Momentum (1-Month)**

| Asset | 1M Return | Signal |
|-------|-----------|--------|
| SPY (Equity) | +3.0% | 📈 Positive |
| TLT (Bonds) | +1.2% | 📈 Positive |
| GLD (Gold) | +10.1% | 📈 Positive |
| UUP (US Dollar) | +0.0% | 📈 Positive |

**Regime:** Mixed/transitional regime

*Last updated: 2026-08-30 18:53 UTC*


---

## 2. Factor Performance Dashboard

*Source: ETF Proxies (MTUM, VLUE, QUAL, USMV, IWM vs SPY)*

*Note: ETF proxy returns include market beta and are not directly comparable to factor-neutral French library returns.*

| Factor | Weekly | 1M | 3M | Mean (52W wkly) | Std (52W wkly) | Z |
|--------|--------|----|----|-----------------|----------------|---|
| Momentum | -1.79% | +0.31% | -4.99% | +0.44% | 2.83% | -0.79 |
| Value | -0.61% | +4.12% | +1.96% | +1.05% | 2.56% | -0.65 |
| Quality | +0.18% | +2.15% | +3.96% | +0.34% | 1.54% | -0.11 |
| Low Volatility | +0.50% | +3.99% | +5.65% | +0.18% | 1.16% | +0.28 |
| Size | -1.87% | -2.55% | +0.09% | +0.11% | 1.50% | -1.32 |

No factor stress signals this week (all within ±2σ).

*Last updated: 2026-08-30 18:53 UTC*


---

## 3. Macro Signal Tracker

| Indicator | Current | 1W Change | Signal |
|-----------|---------|-----------|--------|
| HY Spread (OAS) | 263bps | -12bps | ✅ Tightening |
| IG Spread (OAS) | 79bps | -3bps | ✅ Tightening |
| 2s10s Yield Curve | 0.39% | -0.11% | Normal |
| 3M10Y Yield Curve | 0.83% | -0.03% | Normal |
| Fed Funds Rate | 3.63% | N/A | → |
| HY − IG Spread | 184bps | — | Risk sentiment proxy |

**Macro Summary:** Risk-on macro backdrop

*Last updated: 2026-08-30 18:53 UTC*


---

## 4. Quant Research Digest

Three papers I found worth reading this week:

>**Tabular Deep Learning for Algorithmic Trading: Cross-Regime Bayesian Optimisation for Equity Signal Generation** — Joshua Le Grice | [arXiv](https://arxiv.org/abs/2608.27076v1)  

This paper investigates how to optimize hyperparameters for equity prediction models to ensure they remain robust across different market regimes. It's a highly relevant read for anyone building backtesting pipelines, as it tackles the structural problem of models performing well in one environment but failing when market conditions shift.

>**On the approximation of posterior laws in compound loss models by conditional Wasserstein GANs** — Aleksandar Arandjelovic et al. | [arXiv](https://arxiv.org/abs/2608.27229v1)  

The authors propose using conditional Wasserstein GANs to approximate posterior distributions in compound loss models instead of relying on traditional numerical integration or MCMC methods. Computationally, bypassing repeated numerical integration for Bayesian inference offers a much faster way to evaluate complex scenarios.

>**On the hedging problem in general 1D diffusion markets** — Alexis Anagnostakis et al. | [arXiv](https://arxiv.org/abs/2608.25223v1)  

This paper develops a PDE-based hedging framework for European contingent claims in general 1D diffusion markets characterized by scale functions and speed measures rather than standard SDEs. It provides clean analytical conditions for finding minimal hedging capital without assuming standard classical diffusion dynamics.

*Last updated: 2026-08-30 18:53 UTC*


---

## 5. Stat of the Week

| Stat | Value | Context |
|------|-------|---------|
| CBOE Skew Index | 150 | Elevated tail risk (>130) |

The Skew Index hit 150 this week, while 20-day realized volatility on the SPY dropped down to 10.4%. It is interesting to observe this persistent gap between calm daily realized returns and high out-of-the-money option costs. This kind of data divergence is exactly why using tail-risk metrics like CVaR in optimization frameworks is often more mathematically appropriate than relying solely on historical variance.

*Last updated: 2026-08-30 18:53 UTC*


---

*Generated: 2026-08-30 18:53 UTC*