# Lecture 9 — Weighted Average Cost of Capital

## Hook
"Seer stones": PV of single CF and PV of growing perpetuity — "on these two hang all the law and the prophets" — reappear in DCF and NPV.
Two keys to success: numerator (cash flows: amount & timing) and denominator (discount rate).

## What is the discount rate
- Lexicon: required return = cost of capital = hurdle rate = discount rate (r or k).
- Hurdle rate depends on claimant: common → CAPM; preferred → dividend yield; creditors → YTM; mixture → WACC (table builds up across lecture).
- Discount rate penalizes future CFs for inflation, risk/uncertainty, opportunity cost (3-circle Venn).
- Fundamental axiom: risk requires compensation. Discount rate precisely captures opportunity cost; fully compensates for risk.
- = Real return + E(inflation) + risk premium = RF + risk premium.

## Risk-free rate
Theory: riskless return incl. inflation compensation. Practice: Treasury proxy, historical average; or Duff & Phelps Valuation Handbook (e.g., 20-yr Treasury 2.72%, normalized 3.5%).

## Common stock
- Ford risks (commodity, business cycle, rates, recall, labor, litigation…)
- Not all risk rewarded: total = systematic (non-diversifiable, rewarded) + unsystematic (diversified away)
- Risk premium = β × ERP → E(R_i) = RF + β_i[E(R_mkt) − RF] (CAPM); only β changes across assets
- ERP = E(R_mkt) − RF: estimate from historical market minus RF; or Duff & Phelps (~5.5–6.9%)
- β: market β = 1; scatter of stock returns vs market returns, regression slope R_i,t = α + β_i R_mkt,t (stock j steep ≈ 2.0, stock i flat ≈ 0.48)
- Project β: if project resembles firm use firm β; else pure-play comps.
- Unlever/relever: β_A = β_E(E/V) (β_D ≈ 0); β_E = β_A(V/E).
- Example: J&J medical devices using Boston Scientific (β_E 0.98, D 1.3b, E 9.1b) → D/V .125, β_A .86; relever at D/V .3 → β_E 1.23; k_E = 6% + 1.23 × 6.9% = 14.5%
- Estimating Beta Excel Lab

## Preferred and debt
- R_P = D/P0 (PFF ETF reference)
- R_D = weighted avg YTM on long-term debt (finra.org); issuance costs usually ignored; fallback: debt footnote / market data

## WACC
WACC = (E/V)R_E + (D/V)R_D(1 − T) + (P/V)R_P; market values; marginal tax rate.
Tax proof: $100,000 debt at 10%, T 35% → interest 10,000, tax saving 3,500, after-tax 6.5%.
Ties back to L7 "tax benefits of debt captured in the discount rate".

## Note
Slides 43–51 marked "For Use in Four-Day Training Only" (borrowed from another deck).
