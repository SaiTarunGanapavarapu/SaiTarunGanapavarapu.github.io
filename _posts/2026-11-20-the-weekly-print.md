---
layout: post
title: "The Weekly Print"
date: 2026-11-20
categories: [quant, weekly]
excerpt: "Auto-generated weekly quant memo: market regime, factor performance, macro signals, and research digest for the week of November 20, 2026."

---

## 1. Market Regime Snapshot

**VIX Term Structure**

| Tenor | Level | vs. Spot |
|-------|-------|----------|
| VIX Spot | 35.9 | — |
| VIX 3M | 30.9 | -4.9 (Backwardation) |

**Realized vs. Implied Vol:** SPY 20D RV = 26.3%, VIX = 35.9. Spread = -9.6pp (realized vol below implied — calmer than feared).

**Cross-Asset Momentum (1-Month)**

| Asset | 1M Return | Signal |
|-------|-----------|--------|
| SPY (Equity) | -9.2% | 📉 Negative |
| TLT (Bonds) | +0.6% | 📈 Positive |
| GLD (Gold) | -11.9% | 📉 Negative |
| UUP (US Dollar) | +2.3% | 📈 Positive |

**Regime:** Mixed/transitional regime

*Last updated: 2026-11-24 20:25 UTC*


---

## 2. Factor Performance Dashboard

*Source: ETF Proxies (MTUM, VLUE, QUAL, USMV, IWM vs SPY)*

*Note: ETF proxy returns include market beta and are not directly comparable to factor-neutral French library returns.*

| Factor | Weekly | 1M | 3M | Mean (52W wkly) | Std (52W wkly) | Z |
|--------|--------|----|----|-----------------|----------------|---|
| Momentum 🚨 | -11.34% | -16.46% | -19.64% | +0.07% | 3.82% | -2.99 |
| Value 🚨 | -9.83% | -11.98% | -14.35% | +0.63% | 3.10% | -3.37 |
| Quality 🚨 | -7.41% | -7.61% | -7.09% | +0.18% | 1.83% | -4.14 |
| Low Volatility 🚨 | -5.67% | -5.13% | -3.00% | +0.14% | 1.51% | -3.83 |
| Size | +1.08% | +2.71% | -4.69% | +0.12% | 1.59% | +0.61 |

🚨 **Factor Stress:** Momentum (z=-2.99), Value (z=-3.37), Quality (z=-4.14), Low Volatility (z=-3.83) — weekly return ≥ 2σ from trailing mean.

*Last updated: 2026-11-24 20:25 UTC*


---

## 3. Macro Signal Tracker

| Indicator | Current | 1W Change | Signal |
|-----------|---------|-----------|--------|
| HY Spread (OAS) | 376bps | +53bps | ⚠️ Widening |
| IG Spread (OAS) | 98bps | +9bps | ⚠️ Widening |
| 2s10s Yield Curve | 0.29% | +0.02% | Normal |
| 3M10Y Yield Curve | 0.60% | -0.23% | Normal |
| Fed Funds Rate | 3.88% | N/A | → |
| HY − IG Spread | 278bps | — | Risk sentiment proxy |

**Macro Summary:** Neutral macro backdrop

*Last updated: 2026-11-24 20:25 UTC*


---

## 4. Quant Research Digest

Three papers I found worth reading this week:

>**Cleaning correlation matrices with external information: the Maximum Variance estimator** — Sébastien Valeyre | [arXiv](https://arxiv.org/abs/2611.30843v1)  

This paper introduces an estimator that uses external group labels (like asset classes or regions) to denoise the eigenvectors of an empirical correlation matrix, going beyond standard rotationally invariant estimators that only shrink eigenvalues. As I work on robust covariance estimation for my portfolio optimization code, this is a clean mathematical reminder that eigenvector noise is just as destructive as eigenvalue noise when inverting a sample matrix.

>**Wasserstein Penalisation as an Endogenous Breadth Constraint in Penalised Mean-Variance Portfolio Selection** — Jiahao Chen | [arXiv](https://arxiv.org/abs/2611.30046v1) 

The author proves that in a long-only, penalised mean-variance setup, adding a Wasserstein distributionally robust penalty reduces to a function of the weight vector alone—meaning the robustness radius effectively just prices portfolio breadth. It is a great theoretical result for anyone coding up robust optimization solvers, as it strips away the black-box mystery and shows exactly what the Wasserstein term is actually doing on the simplex.

>**Marked INAR model and the rough Hawkes--Heston limit** — Xiaoyu Wang et al. | [arXiv](https://arxiv.org/abs/2611.29565v1)  

This paper builds a discrete-time Monte Carlo simulator for the rough Hawkes-Heston volatility model using a block FFT scheme to evaluate the excitation convolution in $O(N\log^2 N)$ time per path. It is a very practical numerical methods read for students implementing rough volatility models, where naive convolution loops usually blow up computation time.

*Last updated: 2026-11-24 20:25 UTC*


---

## 5. Stat of the Week

| Stat | Value | Context |
|------|-------|---------|
| Momentum / Low Vol 20D correlation | 0.63 | Crowded defensives signal |

For the first time in weeks, the 20-day correlation between Momentum and Low Volatility crossed the 0.60 threshold to hit 0.63, right as the VIX spiked to 35.9 in deep backwardation and four out of five factors flashed severe stress signals (with Quality and Low Vol dropping -4.14σ and -3.83σ). As I study factor construction and backtesting, seeing these two factors converge during a sharp selloff is a textbook example of how correlations spike toward 1 under stress. It is a solid reminder that assuming static orthogonality between factors in a portfolio model will quickly break down when the market regime shifts.

*Last updated: 2026-11-24 20:25 UTC*


---

*Generated: 2026-11-24 20:25 UTC*