# Lecture 8 — Scenario, Sensitivity, and Simulation Analysis

## Narrative
Past lectures: buying/selling assets, go/no-go; value = Σ PV of expected future CFs.
Lingering problem: "All models are wrong, but some are useful" (Box) — outputs sensitive to inputs; inputs are forecasts; forecast error inevitable.
CAUTION slide: Never make a decision based on a singular output derived from static inputs.

## Scenario analysis
Consider multiple future states. Minimum: Base (best guess), Worst (all inputs against), Best (all inputs align). Solar panel example (Excel).

## Sensitivity analysis
Outputs highly sensitive to few key inputs. Identify key inputs; perturb individually and jointly; re-estimate. Solar panel example (Excel data tables).

## Simulation analysis
"Sensitivity analysis on steroids" — Excel data tables limited to two variables and coarse granularity.
Steps: identify key inputs → replace each with probability distribution → run 1000s of iterations → histogram of outputs → inform decision. Solar panel example.

## Probability primer
- Distribution: outcomes on x, probability on y; P=1 certain, P=0 impossible; sum to 1; area to the left = cumulative probability.
- Normal: four moments (mean, SD, skewness, kurtosis); normal fully defined by mean & SD (skew 0, kurtosis 3). Sample mean & SD formulas. Male/female height distributions.
- 68-95-99.7 rule: US male height mean 70", SD 4" → 68% in 66–74, 95% in 62–78, 99.7% in 58–82.

## Enhancements
Correlation between dynamic inputs; fitting distributions to past data.

## Note
Solar Panel case is the running example across L3 → L7 → L8. Lecture 3 base: cost $10,000; savings $1,500/yr × 15; salvage $2,000; r 6%.
