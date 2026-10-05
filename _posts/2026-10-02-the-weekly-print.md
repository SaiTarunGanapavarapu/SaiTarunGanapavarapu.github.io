---
layout: post
title: "The Weekly Print"
date: 2026-10-02
categories: [quant, weekly]
excerpt: "Auto-generated weekly quant memo: market regime, factor performance, macro signals, and research digest for the week of October 2, 2026."

---

## 1. Market Regime Snapshot

**VIX Term Structure**

| Tenor | Level | vs. Spot |
|-------|-------|----------|
| VIX Spot | 15.3 | — |
| VIX 3M | 18.0 | +2.7 (Contango) |

**Realized vs. Implied Vol:** SPY 20D RV = 10.4%, VIX = 15.3. Spread = -5.0pp (realized vol below implied — calmer than feared).

**Cross-Asset Momentum (1-Month)**

| Asset | 1M Return | Signal |
|-------|-----------|--------|
| SPY (Equity) | -0.2% | 📉 Negative |
| TLT (Bonds) | -5.2% | 📉 Negative |
| GLD (Gold) | -7.3% | 📉 Negative |
| UUP (US Dollar) | +3.1% | 📈 Positive |

**Regime:** Mixed/transitional regime

*Last updated: 2026-10-05 11:31 UTC*


---

## 2. Factor Performance Dashboard

*Source: ETF Proxies (MTUM, VLUE, QUAL, USMV, IWM vs SPY)*

*Note: ETF proxy returns include market beta and are not directly comparable to factor-neutral French library returns.*

| Factor | Weekly | 1M | 3M | Mean (52W wkly) | Std (52W wkly) | Z |
|--------|--------|----|----|-----------------|----------------|---|
| Momentum | +1.38% | +8.92% | +0.57% | +0.49% | 2.81% | +0.31 |
| Value | -0.71% | -0.46% | +3.69% | +0.93% | 2.60% | -0.63 |
| Quality | +0.40% | +1.61% | +2.96% | +0.29% | 1.55% | +0.07 |
| Low Volatility | -0.13% | -2.42% | +0.66% | +0.10% | 1.19% | -0.19 |
| Size | +0.06% | -4.81% | -8.06% | +0.03% | 1.55% | +0.02 |

No factor stress signals this week (all within ±2σ).

*Last updated: 2026-10-05 11:31 UTC*


---

## 3. Macro Signal Tracker

| Indicator | Current | 1W Change | Signal |
|-----------|---------|-----------|--------|
| HY Spread (OAS) | 310bps | +17bps | ⚠️ Widening |
| IG Spread (OAS) | 85bps | +4bps | ⚠️ Widening |
| 2s10s Yield Curve | 0.45% | +0.09% | Normal |
| 3M10Y Yield Curve | 1.09% | +0.16% | Normal |
| Fed Funds Rate | 3.75% | N/A | → |
| HY − IG Spread | 225bps | — | Risk sentiment proxy |

**Macro Summary:** Neutral macro backdrop

*Last updated: 2026-10-05 11:31 UTC*


---

## 4. Quant Research Digest

Three papers I found worth reading this week:

>**When a Correct Reward Is Not Enough: Diagnosing and Guiding PPO in an Analytically Solved Broker-Trader Game** — Siu Tung Wong et al. | [arXiv](https://arxiv.org/abs/2610.03598v1)  

This paper evaluates whether Reinforcement Learning models (specifically PPO) can leverage established analytical solutions in financial optimal-control problems to guide their training. It is an excellent read for anyone building RL trading agents, highlighting that providing a correct reward function is often insufficient without structural mathematical guidance to help the model escape local optima.

>**Mixture-of-Experts for Cryptocurrency Order Execution: Training Stability, Tail Risk, and Failure Modes** — Alexander Ardaiz et al. | [arXiv](https://arxiv.org/abs/2610.03369v1)  

The authors benchmark Double Deep Q-Learning against partitioned Mixture-of-Experts architectures using high-frequency limit order book data to optimize trade execution. This is highly practical for execution research because it emphasizes evaluating model stability across different training seeds and documenting tail-risk failure modes, rather than just reporting the one lucky backtest that achieved the highest return.

>**Event History Over Scale: Compact Transformers for Low-Latency Limit Order Book Forecasting** — David Schaurecker et al. | [arXiv](https://arxiv.org/abs/2610.02917v1)  

This research introduces highly compact, causal transformer architectures (down to 7,203 parameters) specifically optimized for the strict latency constraints of intraday order book forecasting. It tackles a very real engineering bottleneck in deployment, proving that squeezing predictive quality out of tiny, fast architectures is often more useful in production environments than blindly scaling up parameter counts.

*Last updated: 2026-10-05 11:32 UTC*


---

## 5. Stat of the Week

| Stat | Value | Context |
|------|-------|---------|
| CBOE Skew Index | 145 | Elevated tail risk (>130) |

The Skew Index remained elevated at 145 this week, continuing to diverge from the relatively calm 10.4% realized volatility on the SPY. With high-yield spreads also widening 17 basis points to 310bps, it is interesting to observe persistent stress pricing in out-of-the-money puts and credit markets while the top-level equity index barely moves. This divergence is a clean structural reminder to monitor cross-asset metrics and implied tails rather than relying solely on rolling equity variance to evaluate market risk.

*Last updated: 2026-10-05 11:32 UTC*


---

*Generated: 2026-10-05 11:32 UTC*