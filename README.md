# Varnika Bethireddy

Business analytics graduate student at the University of Maryland (Robert H. Smith School of
Business), working toward a data analyst / BI role. I like problems where the answer has to
survive contact with a stakeholder — which usually means getting the data model right first,
then being careful about what the numbers actually support.

## Projects

**[WMATA Transit Performance Analytics](https://github.com/Varnika-2709/wmata-transit-performance-analytics)**
A relational data model and SQL analytics suite over six years of Metrobus performance data
(FY2019–FY2024). Entity design, keys, business rules and referential-integrity actions, plus
four queries answering real operating questions: which routes never recovered from COVID,
which ones burn money without recovering cost, where weekend service is misallocated, and
where reliability is worst for riders with the fewest alternatives.
`SQL · data modeling · ERD · Python (PDF/OCR extraction)`

**[Yelp Review Usefulness Prediction](https://github.com/Varnika-2709/yelp-review-usefulness-prediction)**
Predicting which of 1.58M Yelp reviews get voted useful — 12% positive class, under a hard
constraint that the 95th-percentile *bootstrap* false positive rate stay below 0.10. That
constraint is the interesting part: a threshold tuned on a point estimate crosses the ceiling
about half the time on resampling, so the threshold is chosen against the bootstrapped
distribution instead. Four-model ensemble over 40 leakage-free features.
`Python · pandas · scikit-learn · LightGBM · XGBoost · PyTorch`

**[Mortgage Default Risk Analysis](https://github.com/Varnika-2709/mortgage-default-risk-analysis)**
Fannie Mae loan-level data, 2007Q4 versus 2019Q4, asking what actually predicts default and
what changed after the crisis. Credit score dominates (sub-660 borrowers default at 3–5× the
rate of 780+), leverage compounds it, and the 2019 cohort improved on both counts — partly
better screening, partly a borrower pool that shifted upward.
`R · tidyverse · ggplot2 · plotly · gganimate`

## Tools

**Data & querying** — SQL, relational data modeling, ERD design, referential integrity
**Python** — pandas, NumPy, scikit-learn, LightGBM, XGBoost, PyTorch
**R** — tidyverse, ggplot2, plotly, gganimate, R Markdown
**Visualization & BI** — Tableau, interactive reporting

## Contact

varniii2709@gmail.com
