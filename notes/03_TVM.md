# Lecture 3 — Time Value of Money

## Hooks
Blu-ray player $999.99 (2006) → $60 (2016); gold price chart; "How much would you pay today for my promise of $1,000 in 5 years?"

## Narrative
Value = f(utility); utility of financial asset = future cash flows. Three challenges: which cash flows (L1–2), time (this lecture), uncertainty (later).

## Core
- PV = CF_t/(1+r)^t ("keystone" arch visual)
- Zero-coupon example: $1,000 in 5 yrs at 4% → $821.93
- FV build-up table: $5,000 at 10% for 10 years → $12,968.71 (PV(1+r)^t column)
- Interpretation: indifference between $5,000 now and $12,968.71 in 10 years at 10%
- Value = sum of PVs of expected future cash flows: map cash flows, discount each

## TVM basics
- 5 variables (N, I/Y, PV, PMT, FV) — know 4, solve the 5th; timeline diagram
- Keys to success: signs, calculator language, cash-flow timeline
- Sign conventions (3 problem types):
  - Loans: PV +, PMT −, FV −
  - Investments: PV −, PMT −, FV +
  - Annuity streams: PV −, PMT +, FV +
- Calculator language: financial calc (N total periods, I/Y annual, P/Y, C/Y, BGN); graphing calc; Excel (Rate = PERIODIC, Nper total, Type)
- Firm valuation example: $1.2M/yr for 10 yrs + $5.3M sale in yr 10, r = 7.5% (solution in Excel)

## Rates
- APR (stated, no compounding) vs EAR (captures compounding)
- EAR = (1 + APR/m)^m − 1; APR = [(1+EAR)^(1/m) − 1] × m
- Credit card example (daily compounding)
- IMPORTANT: TVM problems assume stated rates (APR); if using EAR, everything in years

## Practice problems (from slides)
1. Mortgage $225,000, 4.75% APR, 30 yrs, monthly → payment?
2. 401(k) $850/month, EAR 7.5%, 25 years → FV?
3. Solar panels at Flathead Lake: cost $10,000, saves $1,500/yr 15 yrs, salvage $2,000, alt 6% → buy?

## Perpetuities
- Constant and constantly growing; PV_0 = CF_1/(R − g)
- Practice: utility just paid $2.75, g = 2%, r = 8.5% → value/share (note CF_1 = 2.75 × 1.02)
