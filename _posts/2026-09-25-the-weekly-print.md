---
layout: post
title: "The Weekly Print"
date: 2026-09-25
categories: [quant, weekly]
excerpt: "Auto-generated weekly quant memo: market regime, factor performance, macro signals, and research digest for the week of September 25, 2026."

---

## 1. Market Regime Snapshot

**VIX Term Structure**

| Tenor | Level | vs. Spot |
|-------|-------|----------|
| VIX Spot | 14.9 | — |
| VIX 3M | 17.9 | +3.1 (Contango) |

**Realized vs. Implied Vol:** SPY 20D RV = 10.8%, VIX = 14.9. Spread = -4.1pp (realized vol below implied — calmer than feared).

**Cross-Asset Momentum (1-Month)**

| Asset | 1M Return | Signal |
|-------|-----------|--------|
| SPY (Equity) | +0.3% | 📈 Positive |
| TLT (Bonds) | -4.2% | 📉 Negative |
| GLD (Gold) | -6.9% | 📉 Negative |
| UUP (US Dollar) | +2.1% | 📈 Positive |

**Regime:** Mixed/transitional regime

*Last updated: 2026-09-28 21:38 UTC*


---

## 2. Factor Performance Dashboard

*Source: ETF Proxies (MTUM, VLUE, QUAL, USMV, IWM vs SPY)*

*Note: ETF proxy returns include market beta and are not directly comparable to factor-neutral French library returns.*

| Factor | Weekly | 1M | 3M | Mean (52W wkly) | Std (52W wkly) | Z |
|--------|--------|----|----|-----------------|----------------|---|
| Momentum | +2.87% | +4.98% | -2.03% | +0.47% | 2.81% | +0.85 |
| Value | +0.89% | +0.37% | +1.25% | +1.00% | 2.60% | -0.04 |
| Quality | +2.01% | +0.11% | +4.87% | +0.32% | 1.56% | +1.09 |
| Low Volatility | -0.05% | -2.84% | +2.78% | +0.12% | 1.19% | -0.14 |
| Size | -2.00% | -6.32% | -11.16% | +0.02% | 1.54% | -1.31 |

No factor stress signals this week (all within ±2σ).

*Last updated: 2026-09-28 21:38 UTC*


---

## 3. Macro Signal Tracker

| Indicator | Current | 1W Change | Signal |
|-----------|---------|-----------|--------|
| HY Spread (OAS) | 293bps | +25bps | ⚠️ Widening |
| IG Spread (OAS) | 81bps | +4bps | ⚠️ Widening |
| 2s10s Yield Curve | 0.36% | +0.11% | Normal |
| 3M10Y Yield Curve | 0.93% | +0.06% | Normal |
| Fed Funds Rate | 3.63% | N/A | → |
| HY − IG Spread | 212bps | — | Risk sentiment proxy |

**Macro Summary:** Neutral macro backdrop

*Last updated: 2026-09-28 21:38 UTC*


---

## 4. Quant Research Digest

Three papers I found worth reading this week:

>**Taming the Option Factor Zoo: A High-Dimensional Analysis** — Alexander Walter et al. | [arXiv](https://arxiv.org/abs/2609.31263v1)  

The authors construct 137 different option-implied characteristics to test how much of the derivatives cross-section is actually spanned by standard equity factors. For anyone looking at option credit spreads or building derivative pricing models, this is a highly useful dataset for isolating which volatility signals provide genuinely unique information rather than just mirroring equity beta.

>**Cost-Sensitive Online Window Size Selection for Portfolio Management** — Yi-Chen Liu et al. | [arXiv](https://arxiv.org/abs/2609.29887v1)  

This paper proposes a two-level online learning framework to dynamically aggregate portfolio weights using different historical lookback windows. It offers a practical algorithmic alternative to hard-coding a static rolling window in quantitative portfolio optimization scripts, especially when trying to adapt to rapidly changing market variance.

>**Same Text, Different Numbers: The Divergence of LLM-Based Measures** — Hamid Boustanifar et al. | [arXiv](https://arxiv.org/abs/2609.31013v1)  

This study tests how much NLP-derived financial metrics (like sentiment or risk) change simply by swapping the underlying large language model used for extraction. It serves as a good structural reminder that treating LLM outputs as static ground-truth variables introduces hidden, model-dependent noise into quantitative testing pipelines.

*Last updated: 2026-09-28 21:38 UTC*


---

## 5. Stat of the Week

| Stat | Value | Context |
|------|-------|---------|
| CBOE Skew Index | 145 | Elevated tail risk (>130) |

High-yield spreads widened by 25 basis points this week, pushing up to 293bps, while the CBOE Skew Index held elevated at 145. At the same time, 20-day realized volatility on the SPY remains subdued at 10.8%. It is an interesting structural divergence to log: credit markets and out-of-the-money put pricing are showing measurable stress, even as the day-to-day equity index prints stay relatively calm.

*Last updated: 2026-09-28 21:38 UTC*


---

*Generated: 2026-09-28 21:38 UTC*