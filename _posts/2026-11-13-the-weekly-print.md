---
layout: post
title: "The Weekly Print"
date: 2026-11-13
categories: [quant, weekly]
excerpt: "Auto-generated weekly quant memo: market regime, factor performance, macro signals, and research digest for the week of November 13, 2026."

---

## 1. Market Regime Snapshot

**VIX Term Structure**

| Tenor | Level | vs. Spot |
|-------|-------|----------|
| VIX Spot | 19.3 | — |
| VIX 3M | 20.6 | +1.3 (Contango) |

**Realized vs. Implied Vol:** SPY 20D RV = 22.1%, VIX = 19.3. Spread = +2.8pp (realized vol above implied — elevated realized fear).

**Cross-Asset Momentum (1-Month)**

| Asset | 1M Return | Signal |
|-------|-----------|--------|
| SPY (Equity) | -1.2% | 📉 Negative |
| TLT (Bonds) | -0.4% | 📉 Negative |
| GLD (Gold) | -7.0% | 📉 Negative |
| UUP (US Dollar) | +2.0% | 📈 Positive |

**Regime:** Mixed/transitional regime

*Last updated: 2026-11-16 22:15 UTC*


---

## 2. Factor Performance Dashboard

*Source: ETF Proxies (MTUM, VLUE, QUAL, USMV, IWM vs SPY)*

*Note: ETF proxy returns include market beta and are not directly comparable to factor-neutral French library returns.*

| Factor | Weekly | 1M | 3M | Mean (52W wkly) | Std (52W wkly) | Z |
|--------|--------|----|----|-----------------|----------------|---|
| Momentum | +6.62% | -9.82% | -15.40% | +0.22% | 3.51% | +1.83 |
| Value | +3.84% | -3.24% | -6.84% | +0.74% | 2.79% | +1.11 |
| Quality | +2.17% | -1.16% | -0.03% | +0.27% | 1.52% | +1.25 |
| Low Volatility 🚨 | +2.84% | +2.48% | +4.03% | +0.22% | 1.28% | +2.04 |
| Size | -1.13% | +3.24% | -6.48% | +0.08% | 1.59% | -0.76 |

🚨 **Factor Stress:** Low Volatility (z=+2.04) — weekly return ≥ 2σ from trailing mean.

*Last updated: 2026-11-16 22:15 UTC*


---

## 3. Macro Signal Tracker

| Indicator | Current | 1W Change | Signal |
|-----------|---------|-----------|--------|
| HY Spread (OAS) | 323bps | -19bps | ✅ Tightening |
| IG Spread (OAS) | 89bps | -4bps | ✅ Tightening |
| 2s10s Yield Curve | 0.27% | -0.11% | Normal |
| 3M10Y Yield Curve | 0.83% | +0.16% | Normal |
| Fed Funds Rate | 3.88% | N/A | → |
| HY − IG Spread | 234bps | — | Risk sentiment proxy |

**Macro Summary:** Risk-on macro backdrop

*Last updated: 2026-11-16 22:15 UTC*


---

## 4. Quant Research Digest

Three papers I found worth reading this week:

>**Short Windows, Unmodelled Costs, Unknown Cutoffs: A Pre-Registered Evidence Audit of 91 LLM Trading Papers** — Henry Zhang | [arXiv](https://arxiv.org/abs/2611.18934v1)  

This paper systematically audits the methodology of recent research claiming massive Sharpe ratios for LLM-based trading agents, exposing structural flaws like ignored transaction costs and cherry-picked data windows. As I build out my own Python backtesting engines, this is a crucial reality check on why rigorous out-of-sample testing and strict cost modeling are absolutely non-negotiable before trusting any algorithmic signal.

>**Implied volatility models without static arbitrage** — Michał Barski et al. | [arXiv](https://arxiv.org/abs/2611.18937v1)  

The authors derive explicit mathematical formulas for the probabilities of calendar spread and butterfly arbitrage within Gaussian factor models of implied volatility surfaces. It is a highly relevant breakdown for anyone analyzing options credit spreads, proving that standard stochastic volatility evolutions often inherently allow for static arbitrage unless strictly constrained.

>**Local Stochastic Volatility Iterations** — Christian Bayer et al. | [arXiv](https://arxiv.org/abs/2611.18214v1)  

This research proposes a calibration method for local stochastic volatility models that uses a fixed-point iteration to determine the leverage factor via single regressions in time and state. For students coding up their own derivative pricing models, it offers a computationally efficient alternative to traditional, heavier calibration techniques.

*Last updated: 2026-11-16 22:15 UTC*


---

## 5. Stat of the Week

| Stat | Value | Context |
|------|-------|---------|
| CBOE Skew Index | 147 | Elevated tail risk (>130) |

The Skew Index sits at a high 147, but what really stands out to me this week is the realized-to-implied volatility spread. With 20-day realized volatility on the SPY spiking to 22.1% while the VIX lags at just 19.3%, we are seeing a rare environment where realized market turbulence is actually outpacing forward-looking implied options pricing. As I study volatility risk premiums for my quantitative research repositories, this inversion is a fascinating reminder that implied volatility isn't an unbreakable upper bound on actual market fear.

*Last updated: 2026-11-16 22:15 UTC*


---

*Generated: 2026-11-16 22:15 UTC*
