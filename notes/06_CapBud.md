# Lecture 6 — Capital Budgeting Basics

## Narrative
Deployment → Go/No-Go decisions (Ch. 9): whether to launch; choose among competing projects. Initial outlay = cost; future CFs = benefits; go/no-go is fundamentally a valuation exercise.

## Tools covered
NPV, Payback, Discounted payback, IRR, MIRR (not covered: AAR, PI). Colour-coded per tool on slides.

## Definitions & rules
- Payback: time to recover initial investment; lower better; interpolate.
- Discounted payback: same using PVs.
- NPV = CF0 + Σ CF_t/(1+r)^t; map CFs, PV each, sum. Excel NPV glitch (discounts first CF — workaround: =NPV(r, CF1:CFn)+CF0). Rule: >0 go; <0 no-go; mutually exclusive → highest NPV.
- Lexicon: investor's required return = corporation's cost of capital = hurdle rate = discount rate = r (time value of money).
- IRR: rate making NPV = 0; IRR > hurdle → go. NPV profile chart (sample: crosses zero ~15.6%).

## Critiques
- Payback: pros easy, liquidity bias, crude risk adjustment; cons no TVM, arbitrary cutoff, multiple paybacks, can accept −NPV.
- Disc. payback: pros TVM, never accepts −NPV; cons arbitrary cutoff, may reject +NPV, "why not just use NPV?"
- NPV: gold standard; cons harder to explain, sensitive to inputs, assumes reinvestment at r.
- IRR: best alternative to NPV; cons reinvestment at IRR, mutually exclusive ranking errors, multiple IRRs for non-conventional CFs.

## Examples
- Mutually exclusive A vs B: A = −100, 50, 40, 40, 30; B = −100, 20, 40, 50, 60 (crossover)
- Utah Jazz free-agent power forward: CF0 −10M; net +7.5, +7.5, +5.5, −0.5, −0.5, −3.5, −4.5, −5.5 (M); r 12% → NPV −41,437; two IRRs (~12.7% and ~35.3%) both > 12% → IRR misleads.
- MIRR #1 discounting (11.848%), #2 reinvestment (11.942%), #3 combination (11.965%) — all < 12%, consistent with −NPV.
- "What they really use" — Graham & Harvey survey table (IRR & NPV dominant).
