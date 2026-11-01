---
layout: post
title: "The Weekly Print"
date: 2026-10-30
categories: [quant, weekly]
excerpt: "Auto-generated weekly quant memo: market regime, factor performance, macro signals, and research digest for the week of October 30, 2026."

---

## 1. Market Regime Snapshot

**VIX Term Structure**

| Tenor | Level | vs. Spot |
|-------|-------|----------|
| VIX Spot | 19.4 | — |
| VIX 3M | 20.8 | +1.4 (Contango) |

**Realized vs. Implied Vol:** SPY 20D RV = 11.6%, VIX = 19.4. Spread = -7.8pp (realized vol below implied — calmer than feared).

**Cross-Asset Momentum (1-Month)**

| Asset | 1M Return | Signal |
|-------|-----------|--------|
| SPY (Equity) | -1.8% | 📉 Negative |
| TLT (Bonds) | +5.6% | 📈 Positive |
| GLD (Gold) | -6.4% | 📉 Negative |
| UUP (US Dollar) | +0.4% | 📈 Positive |

**Regime:** Mixed/transitional regime

*Last updated: 2026-11-01 10:30 UTC*


---

## 2. Factor Performance Dashboard

*Source: ETF Proxies (MTUM, VLUE, QUAL, USMV, IWM vs SPY)*

*Note: ETF proxy returns include market beta and are not directly comparable to factor-neutral French library returns.*

| Factor | Weekly | 1M | 3M | Mean (52W wkly) | Std (52W wkly) | Z |
|--------|--------|----|----|-----------------|----------------|---|
| Momentum | -1.85% | -11.46% | -5.67% | +0.24% | 3.08% | -0.68 |
| Value | +0.62% | -2.98% | +1.25% | +0.82% | 2.56% | -0.08 |
| Quality | -0.15% | -0.43% | +0.55% | +0.25% | 1.50% | -0.26 |
| Low Volatility | -0.02% | +4.99% | +5.09% | +0.23% | 1.21% | -0.20 |
| Size | +1.86% | +1.20% | -5.46% | +0.07% | 1.59% | +1.12 |

No factor stress signals this week (all within ±2σ).

*Last updated: 2026-11-01 10:30 UTC*


---

## 3. Macro Signal Tracker

| Indicator | Current | 1W Change | Signal |
|-----------|---------|-----------|--------|
| HY Spread (OAS) | 326bps | -14bps | ✅ Tightening |
| IG Spread (OAS) | 89bps | +0bps | → Unchanged |
| 2s10s Yield Curve | 0.38% | +0.07% | Normal |
| 3M10Y Yield Curve | 0.78% | +0.00% | Normal |
| Fed Funds Rate | 3.75% | N/A | → |
| HY − IG Spread | 237bps | — | Risk sentiment proxy |

**Macro Summary:** Risk-on macro backdrop

*Last updated: 2026-11-01 10:30 UTC*


---

## 4. Quant Research Digest

Three papers I found worth reading this week:

>**Comparing tail forecasts: the number of exceedances is the sample size** — Raphael Coelho | [arXiv](https://arxiv.org/abs/2610.40366v1)  

This paper demonstrates that when evaluating tail-risk forecasts like expected shortfall, the effective sample size is strictly the number of actual tail exceedances rather than the total number of observations. As I am currently coding up backtests for tail-risk hedges, this is a great statistical reminder that having ten years of daily data doesn't mean much if only a handful of days actually breach the threshold.

>**Sparse Autoencoders as Implicit Diversification Regularisers for Cross-Sectional Cryptocurrency Returns** — Weijia Han et al. | [arXiv](https://arxiv.org/abs/2610.39205v1)  

The authors apply sparse autoencoders (SAEs) to extract a small number of interpretable, active latent features from broad cross-sectional crypto returns. I find this approach highly relevant for my own factor modeling projects, as standard neural network factors usually become a black box that is impossible to interpret or regularize effectively.

>**Mean Field Games of Optimal Trading with an SPDE Model of the Limit Order Book** — Hanchao Liu et al. | [arXiv](https://arxiv.org/abs/2610.38988v1)  

This research formulates optimal trading inside a limit order book using stochastic partial differential equations (SPDEs) to model the bid and ask densities as mean field games. It provides a rigorous mathematical framework for how to think about order flow interaction and market impact when simulating high-frequency trading agents.

*Last updated: 2026-11-01 10:30 UTC*


---

## 5. Stat of the Week

| Stat | Value | Context |
|------|-------|---------|
| CBOE Skew Index | 150 | Elevated tail risk (>130) |

The CBOE Skew Index stayed elevated at 150 this week, even as high-yield spreads tightened and realized volatility on the SPY ticked up only slightly to 11.6%. In my volatility modeling studies, seeing this persistent spread between calm realized index movements and expensive out-of-the-money put pricing is a stark reminder that implied volatility surfaces encode fear of structural breaks, not just historical variance. It proves why plugging simple trailing standard deviations into a Black-Scholes pricer will completely fail to capture real-world tail dynamics.

*Last updated: 2026-11-01 10:30 UTC*


---

*Generated: 2026-11-01 10:30 UTC*