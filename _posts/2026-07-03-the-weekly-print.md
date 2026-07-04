---
layout: post
title: "The Weekly Print"
date: 2026-07-03
categories: [quant, weekly]
excerpt: "Auto-generated weekly quant memo: market regime, factor performance, macro signals, and research digest for the week of July 3, 2026."

---

## 1. Market Regime Snapshot

**VIX Term Structure**

| Tenor | Level | vs. Spot |
|-------|-------|----------|
| VIX Spot | 16.1 | — |
| VIX 3M | 19.0 | +2.9 (Contango) |

**Realized vs. Implied Vol:** SPY 20D RV = 18.1%, VIX = 16.1. Spread = +2.0pp (realized vol above implied — elevated realized fear).

**Cross-Asset Momentum (1-Month)**

| Asset | 1M Return | Signal |
|-------|-----------|--------|
| SPY (Equity) | -1.0% | 📉 Negative |
| TLT (Bonds) | +0.6% | 📈 Positive |
| GLD (Gold) | -7.3% | 📉 Negative |
| UUP (US Dollar) | +1.7% | 📈 Positive |

**Regime:** Mixed/transitional regime

*Last updated: 2026-07-04 17:17 UTC*


---

## 2. Factor Performance Dashboard

*Source: ETF Proxies (MTUM, VLUE, QUAL, USMV, IWM vs SPY)*

*Note: ETF proxy returns include market beta and are not directly comparable to factor-neutral French library returns.*

| Factor | Weekly | 1M | 3M | Mean (52W wkly) | Std (52W wkly) | Z |
|--------|--------|----|----|-----------------|----------------|---|
| Momentum 🚨 | -6.71% | -2.81% | +29.21% | +0.59% | 2.56% | -2.85 |
| Value 🚨 | -5.68% | -4.93% | +33.77% | +1.05% | 2.52% | -2.68 |
| Quality | +2.43% | +1.41% | +13.51% | +0.36% | 1.55% | +1.34 |
| Low Volatility 🚨 | +3.16% | +1.31% | +5.96% | +0.11% | 1.17% | +2.61 |
| Size | -1.89% | +4.02% | +4.96% | +0.25% | 1.55% | -1.38 |

🚨 **Factor Stress:** Momentum (z=-2.85), Value (z=-2.68), Low Volatility (z=+2.61) — weekly return ≥ 2σ from trailing mean.

*Last updated: 2026-07-04 17:17 UTC*


---

## 3. Macro Signal Tracker

| Indicator | Current | 1W Change | Signal |
|-----------|---------|-----------|--------|
| HY Spread (OAS) | 275bps | -3bps | ✅ Tightening |
| IG Spread (OAS) | 75bps | -1bps | ✅ Tightening |
| 2s10s Yield Curve | 0.35% | +0.04% | Normal |
| 3M10Y Yield Curve | 0.63% | +0.11% | Normal |
| Fed Funds Rate | 3.63% | N/A | → |
| HY − IG Spread | 200bps | — | Risk sentiment proxy |

**Macro Summary:** Risk-on macro backdrop

*Last updated: 2026-07-04 17:17 UTC*


---

## 4. Quant Research Digest

Three papers I found worth reading this week:

>**Portfolio Optimization under Fast and Slow Latent Mean-Reverting and Momentum Drift** — Dannin J. Eccles et al | [arXiv](https://arxiv.org/abs/2607.01705v1)  

This paper frames the filtered estimate of an asset's latent drift as the difference between fast and slow moving averages, mapping a standard MACD signal directly to an optimization tracking problem. It provides a highly rigorous mathematical link between intuitive trading rules and formal filtering theory.

>**Is Trend Still Your Friend?: A Microstructural Account of the Demise of Short-Term Trend-Following** — Jutta G. Kurth et al | [arXiv](https://arxiv.org/abs/2607.01550v1)  

The authors document a distinct performance break in short-term trend-following strategies post-2009 using a broad cross-section of futures contracts. It is a useful case study on structural changes in market microstructure and how signal speed impacts decay.

>**Tail Risk Management with Puts and Trend Following: A CVaR Framework for Crashes and Drawdowns** — Miquel Noguer I Alonso et al | [arXiv](https://arxiv.org/abs/2607.00883v1)  

This paper breaks down tail risk management into an allocation problem across distinct loss regimes like sudden market crashes versus prolonged drawdowns. It maps out how to balance option-based protection with trend-following overlays inside a strict optimization framework.

*Last updated: 2026-07-04 17:17 UTC*


---

## 5. Stat of the Week

| Stat | Value | Context |
|------|-------|---------|
| CBOE Skew Index | 150 | Elevated tail risk (>130) |

The factor dashboard showed some serious outliers this week—Momentum and Value dropped by more than two standard deviations, while Low Volatility spiked. At the same time, the Skew Index went up to 150 even though the VIX stayed low at 16.1. It basically looks like a classic defensive shift in the data; the day-to-day market numbers seem calm, but the underlying factor moves and options pricing show people are getting nervous about a big drop.

*Last updated: 2026-07-04 17:17 UTC*


---

*Generated: 2026-07-04 17:17 UTC*