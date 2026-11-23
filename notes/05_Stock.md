# Lecture 5 — Stock Valuation

## Narrative
Deployment → Asset purchases & sales (Ch. 7–8). Buy low/sell high = seeking abnormal risk-adjusted returns; needs occasional mispricing, tools to identify it, realistic expectation of convergence.
Price = Σ CF_t/(1+r)^t. Questions: which cash flows, how to forecast, infinite horizon, time, risk.
Possibilities: Method of Comparables, Dividend models, DCF (FCF), REM (earnings), others.

## Method of Comparables (MOC)
Steps: (1) understand target (2) pick comps (3) choose proxy (EPS, sales…) (4) market value per $ proxy for each comp (5) average (6) × target proxy.
Like: simple, no forecasting. Concerns: true comps, negative denominators, right proxy, market efficiency. Best for private firms with public comps.

## Dividend models
- Zero growth: P = D/r
- Constant growth (Gordon): P0 = D1/(r − g)
- Two-stage: Σ D_t/(1+r)^t to T + [D_{T+1}/(r − g)]/(1+r)^T
Like: sound theory. Concerns: low/no dividends, manipulable, not reflective of value added. Best for steady dividend payers (utilities, preferred).

## DCF
Dividends vs FCF: FCF paid to shareholders & creditors, less choice, harder to manipulate, better measure of value creation.
Equity value = Σ FCF_t/(1+r)^t + [FCF_{T+1}/(r − g)]/(1+r)^T − D0 (market value of debt); per share ÷ shares.
Concerns: FCF hard to forecast, steady-state g hard, very sensitive to g. Best for firms with forecastable FCF.

## Steady-state growth digression
Econ 101: abnormal growth mean-reverts → expect average growth → ΔGDP.
- Simple: r = (GDP_t/GDP_0)^(1/t) − 1 (only uses endpoints — the problem)
- Regression: ln(GDP_t) = ln(GDP_0) + t·ln(1+r); slope m → r = e^m − 1

## Football field
Estimates (Low/High): MOC-EPS 28–32; MOC-Sales 27–33; DDM 24–30; DCF 29–37; REM 28–36 → overlap ~$29–$30.
(Slide label reads "$29 > Intrinsic Value > $30" — likely intended $29 < IV < $30.)

All worked examples in Excel file "Stock Valuation Basics Final" (not uploaded).
