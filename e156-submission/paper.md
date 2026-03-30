Mahmood Ahmad
Tahir Heart Institute
author@example.com

CT.gov Risk-Adjusted Hiddenness

Which CT.gov portfolios remain quieter than expected after adjusting for study mix instead of comparing raw rates alone? We analysed 249,507 eligible older closed interventional studies from the March 29, 2026 full-registry snapshot. We fit logistic models for missing results and ghost protocols using phase, purpose, allocation, status, enrollment, arm count, intervention count, geography scale, outcome density, and study age, excluding sponsor and geography identities from adjustment. After adjustment, No-US portfolios still carried 16,659 excess no-results studies, while OTHER held the largest sponsor-class excess stock at 3,652 and OTHER_GOV the worst excess rate at 17.1 percentage points. Industry fell below expectation on no-results by 3,314 studies yet above expectation on ghost protocols by 3,051, suggesting residual hiddenness concentrates in fully invisible studies. Study mix therefore explains part of the backlog, but large sponsor and geography residuals still remain after adjustment. These models use registry-visible design fields and estimate excess hiddenness, not causal blame or legal liability.

Outside Notes

Type: methods
Primary estimand: Excess missing-results stock over model-expected missing-results counts among eligible older CT.gov studies
App: CT.gov Risk-Adjusted Hiddenness dashboard
Data: 249,507 eligible older closed interventional studies with design-mix adjustment excluding sponsor and geography identities
Code: https://github.com/mahmood726-cyber/ctgov-risk-adjusted-hiddenness
Version: 1.0.0
Validation: FULL REGISTRY RUN

References

1. ClinicalTrials.gov API v2. National Library of Medicine. Accessed March 29, 2026.
2. DeVito NJ, Bacon S, Goldacre B. Compliance with legal requirement to report clinical trial results on ClinicalTrials.gov: a cohort study. Lancet. 2020;395(10221):361-369.
3. Zarin DA, Tse T, Williams RJ, Carr S. Trial reporting in ClinicalTrials.gov. N Engl J Med. 2016;375(20):1998-2004.

AI Disclosure

This work represents a compiler-generated evidence micro-publication built from structured registry data and deterministic summary code. AI was used as a constrained coding and drafting assistant for interface generation, packaging, and prose refinement, not as an autonomous author. The analytical choices, interpretation, and final outputs were reviewed by the author, who takes responsibility for the content.
