# Is It Worth It? — Corporate Finance Review

**Live site:** https://wrigh1ca-code.github.io/Corp-Fin-Intro/

A review and practice site for an executive MBA introduction to corporate finance. Students watch the recorded lectures, then use this site to review key ideas, work through visual walkthroughs, and practice with problems that generate new numbers every time.

The whole course is framed around one question, *is it worth it?*, and one equation:

> Value = F(E[utility]) = Σ E[CFₜ] / (1 + r)ᵗ

Every lecture page answers one piece of that equation (what cash flows, how to forecast them, when is T, what is the right r) or applies the whole thing (bonds, stocks, projects).

## What's here

| Path | What it is |
|---|---|
| `index.html` | The entire site: one self-contained HTML file (styles, scripts and data inline). No build step. |
| `notes/` | Lecture-by-lecture notes extracted from the slide decks. Source context for future edits. |
| `.nojekyll` | Tells GitHub Pages to serve files as-is. |

## Pages

Home (Lecture 0 and the intro) · 1 Free cash flows to the firm · 2 Percentage of sales forecasting · 3 Time value of money · 4 Bonds · 5 Stock valuation · 6 Capital budgeting · 7 Relevant cash flows · 8 Scenario, sensitivity and simulation · 9 Weighted average cost of capital

Each topic page has, in order:

1. **Key ideas and key equations**: the summary for students who already get it.
2. **Learn it**: interactive teaching graphics for the most important ideas.
3. **Practice problems**: several problem types, randomized numbers, answer checking and worked solutions.
4. **Concept check**: a short multiple-choice quiz with explanations.

Pages are routed by URL hash, e.g. `index.html#wacc`, `index.html#capital-budgeting`.

## Viewing and publishing

- **Locally:** open `index.html` in a browser.
- **GitHub Pages:** served from `main` / root. Every push to `main` republishes the site within a minute or two.

## Editing

Most content lives in plain JavaScript data near the bottom of `index.html`:

- `L`: lecture list (titles, key ideas, key equations)
- `WORTH`: the "Is it worth it?" line on each page
- `LEARN`: teaching graphics, keyed by page id
- `PR`: practice problem generators and concept-check questions, keyed by page id
- Capital budgeting has its own labs, practice and quiz (`PRE`, `TOOLS`, `QZ`)

Numbers from the slides are reproduced exactly where the slides give them; numbers that are not from the slides are labeled as illustrative on the page.
