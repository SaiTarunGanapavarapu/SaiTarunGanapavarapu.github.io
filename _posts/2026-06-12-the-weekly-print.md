---
layout: post
title: "The Weekly Print"
date: 2026-06-12
categories: [quant, weekly]
excerpt: "Auto-generated weekly quant memo: market regime, factor performance, macro signals, and research digest for the week of June 12, 2026."

---

## 1. Market Regime Snapshot

**VIX Term Structure**

| Tenor | Level | vs. Spot |
|-------|-------|----------|
| VIX Spot | 17.7 | — |
| VIX 3M | 20.5 | +2.8 (Contango) |

**Realized vs. Implied Vol:** SPY 20D RV = 15.1%, VIX = 17.7. Spread = -2.6pp (realized vol below implied — calmer than feared).

**Cross-Asset Momentum (1-Month)**

| Asset | 1M Return | Signal |
|-------|-----------|--------|
| SPY (Equity) | -0.9% | 📉 Negative |
| TLT (Bonds) | +1.4% | 📈 Positive |
| GLD (Gold) | -9.5% | 📉 Negative |
| UUP (US Dollar) | +1.2% | 📈 Positive |

**Regime:** Mixed/transitional regime

*Last updated: 2026-06-13 14:54 UTC*

---

## 2. Factor Performance Dashboard

*Source: ETF Proxies (MTUM, VLUE, QUAL, USMV, IWM vs SPY)*

*Note: ETF proxy returns include market beta and are not directly comparable to factor-neutral French library returns.*

| Factor | Weekly | 1M | 3M | Mean (52W wkly) | Std (52W wkly) | Z |
|--------|--------|----|----|-----------------|----------------|---|
| Momentum 🚨 | +5.85% | +6.22% | +33.38% | +0.67% | 2.42% | +2.14 |
| Value | +3.37% | +7.90% | +37.70% | +1.18% | 2.47% | +0.89 |
| Quality | +1.77% | +2.82% | +11.39% | +0.38% | 1.61% | +0.86 |
| Low Volatility | +0.43% | +1.84% | +1.45% | +0.10% | 1.12% | +0.30 |
| Size 🚨 | +3.44% | +3.81% | +6.16% | +0.22% | 1.43% | +2.25 |

🚨 **Factor Stress:** Momentum (z=+2.14), Size (z=+2.25) — weekly return ≥ 2σ from trailing mean.

*Last updated: 2026-06-13 14:54 UTC*

---

## 3. Macro Signal Tracker

| Indicator | Current | 1W Change | Signal |
|-----------|---------|-----------|--------|
| HY Spread (OAS) | 278bps | +4bps | ⚠️ Widening |
| IG Spread (OAS) | 75bps | +1bps | ⚠️ Widening |
| 2s10s Yield Curve | 0.39% | +0.01% | Normal |
| 3M10Y Yield Curve | 0.70% | -0.07% | Normal |
| Fed Funds Rate | 3.63% | N/A | → |
| HY − IG Spread | 203bps | — | Risk sentiment proxy |

**Macro Summary:** Neutral macro backdrop — credit spreads ticking wider but still historically tight; yield curve normal and steepening at the short end.

*Last updated: 2026-06-13 14:54 UTC*

---

## 4. Quant Research Digest

Three papers I found worth reading this week:

**Non-Spanning Identification of Scheduled Event Risk in Option Pricing** — Zhong | [arXiv](https://arxiv.org/abs/2606.12872v1)
There's a subtle bug in how a lot of people estimate event risk around FOMC/CPI/NFP: if your "no-event" baseline surface is fit using quotes that span the event, it ends up eating part of the jump premium without you noticing. Zhong's fix is to just not let that happen — fit the two surfaces on non-overlapping quotes. Obvious in hindsight, but I haven't seen it done cleanly before.

**The Mathematics of Heuristic Portfolio Optimization** — Noguer i Alonso | [arXiv](https://arxiv.org/abs/2606.12612v1)
Basically a proof of why "just use risk parity" isn't lazy — it's a defensible projection of the Markowitz solution under estimation uncertainty. I liked this because it gives a real answer to "when does it actually pay to forecast returns vs. just use a heuristic," instead of the usual hand-wavy answer.

**Realtime Price Impact Detection** — Zovko | [arXiv](https://arxiv.org/abs/2606.13419v1)
Treats "am I moving the market right now" as a live statistical test instead of something you check after the fact. Feels like the obvious way to do it once you read it, which is usually a good sign.

*Last updated: 2026-06-13 14:54 UTC*

---

## 5. Stat of the Week

| Stat | Value | Context |
|------|-------|---------|
| CBOE Skew Index | 143 | Elevated tail risk (>130) |
| Momentum / Low Vol 20D correlation | 0.24 | No crowding signal (< 0.6) |

**Skew at 143, VIX at 17.7 — that gap is the story**

VIX itself is unremarkable, sitting near 18. But Skew at 143 is the highest it's been in a while, and that combination is the interesting part — vol is cheap, but tail protection isn't. Someone out there is paying for a specific bad outcome without believing the *average* week is going to be rough. Worth keeping an eye on whether VIX catches up to that pricing or the skew just bleeds off.

*Last updated: 2026-06-13 14:54 UTC*

---

*Generated: 2026-06-13 14:54 UTC*
