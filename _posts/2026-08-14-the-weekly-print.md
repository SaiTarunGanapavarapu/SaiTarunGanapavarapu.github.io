---
layout: post
title: "The Weekly Print"
date: 2026-08-14
categories: [quant, weekly]
excerpt: "Auto-generated weekly quant memo: market regime, factor performance, macro signals, and research digest for the week of August 14, 2026."

---

## 1. Market Regime Snapshot

**VIX Term Structure**

| Tenor | Level | vs. Spot |
|-------|-------|----------|
| VIX Spot | 14.2 | — |
| VIX 3M | 18.5 | +4.2 (Contango) |

**Realized vs. Implied Vol:** SPY 20D RV = 13.4%, VIX = 14.2. Spread = -0.9pp (realized vol below implied — calmer than feared).

**Cross-Asset Momentum (1-Month)**

| Asset | 1M Return | Signal |
|-------|-----------|--------|
| SPY (Equity) | +4.4% | 📈 Positive |
| TLT (Bonds) | -2.5% | 📉 Negative |
| GLD (Gold) | +9.0% | 📈 Positive |
| UUP (US Dollar) | -0.8% | 📉 Negative |

**Regime:** Mixed/transitional regime

*Last updated: 2026-08-16 17:00 UTC*


---

## 2. Factor Performance Dashboard

*Source: ETF Proxies (MTUM, VLUE, QUAL, USMV, IWM vs SPY)*

*Note: ETF proxy returns include market beta and are not directly comparable to factor-neutral French library returns.*

| Factor | Weekly | 1M | 3M | Mean (52W wkly) | Std (52W wkly) | Z |
|--------|--------|----|----|-----------------|----------------|---|
| Momentum | +2.55% | -5.76% | +3.11% | +0.45% | 2.74% | +0.77 |
| Value | +3.26% | +1.28% | +13.43% | +1.10% | 2.49% | +0.87 |
| Quality | +0.07% | +2.49% | +7.10% | +0.38% | 1.48% | -0.21 |
| Low Volatility | +0.51% | +3.58% | +7.57% | +0.19% | 1.15% | +0.28 |
| Size | +0.76% | -0.18% | +2.31% | +0.25% | 1.54% | +0.33 |

No factor stress signals this week (all within ±2σ).

*Last updated: 2026-08-16 17:00 UTC*


---

## 3. Macro Signal Tracker

| Indicator | Current | 1W Change | Signal |
|-----------|---------|-----------|--------|
| HY Spread (OAS) | 271bps | +0bps | → Unchanged |
| IG Spread (OAS) | 79bps | +1bps | ⚠️ Widening |
| 2s10s Yield Curve | 0.51% | +0.05% | Normal |
| 3M10Y Yield Curve | 0.82% | +0.04% | Normal |
| Fed Funds Rate | 3.63% | N/A | → |
| HY − IG Spread | 192bps | — | Risk sentiment proxy |

**Macro Summary:** Neutral macro backdrop

*Last updated: 2026-08-16 17:01 UTC*


---

## 4. Quant Research Digest

Three papers I found worth reading this week:

>**FlowLOB: Efficient and Controllable Limit Order Book Generation with Flow Matching** — Zhuohan Wang et al. | [arXiv](https://arxiv.org/abs/2608.13096v1)  

The authors use flow-matching to generate synthetic limit order book trajectories that can effectively transfer to unseen instruments. Generating realistic market data is a notoriously difficult hurdle for accurate backtesting, so seeing a model successfully reproduce LOB dynamics across different sampling frequencies makes for a great technical reference.

>**DYSANOS Generative Dynamic Smooth Arbitrage-free Non-parametric Option Surfaces** — Hans Buehler et al. | [arXiv](https://arxiv.org/abs/2608.12587v1)  

This paper introduces a generative market model capable of simulating smooth, static-arbitrage-free option surfaces across various strikes and expiries. Many standard volatility models introduce arbitrage opportunities when pushed to generate long-term paths, making this a useful framework for modeling extended option price trajectories without breaking underlying assumptions.

>**Diffusion Models in Finance: A Survey** — Zhuohan Wang et al. | [arXiv](https://arxiv.org/abs/2608.12583v1)  

This is a comprehensive survey on the application of diffusion generative models in financial data, specifically highlighting their alignment with stochastic differential equations. It provides a clean, mathematical overview of why diffusion models are increasingly becoming the standard for complex financial modeling architectures.

*Last updated: 2026-08-16 17:01 UTC*


---

## 5. Stat of the Week

| Stat | Value | Context |
|------|-------|---------|
| CBOE Skew Index | 138 | Elevated tail risk (>130) |

The Skew Index is sitting at 138 this week while the VIX remains relatively low at 14.2. This divergence between calm realized volatility and an elevated skew is a great structural reminder of why assuming normal distributions in return forecasting can be dangerous. It is exactly the kind of environment where optimizing for CVaR instead of standard mean-variance makes a practical mathematical difference.

*Last updated: 2026-08-16 17:01 UTC*


---

*Generated: 2026-08-16 17:01 UTC*