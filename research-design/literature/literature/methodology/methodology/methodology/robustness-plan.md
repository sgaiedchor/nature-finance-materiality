# Robustness and Validation Plan

## 1. General Principle

Robustness analysis is integrated into the research design rather than added after
the main results are obtained.

The objective is to distinguish findings that are stable across reasonable analytical
choices from findings that depend on a specific specification.

---

## 2. A1 — Bibliometric Robustness

Potential checks include:

- alternative search queries;
- alternative temporal windows;
- keyword-frequency thresholds;
- alternative network normalisation;
- alternative community detection;
- thematic-cluster stability;
- alternative entropy measures;
- alternative TNFCI specifications;
- permutation tests;
- null-model comparison.

---

## 3. A2 — Measurement Robustness

Potential checks include:

- alternative ESG measures;
- alternative biodiversity measures;
- alternative exposure definitions;
- winsorisation;
- lagged variables;
- sector × year controls;
- country × year controls;
- influential-observation exclusions;
- linear benchmarks;
- machine-learning benchmarks;
- information-block ablations;
- NLP human validation.

---

## 4. A3 — Causal Robustness

Potential checks include:

- pre-treatment trends;
- event-study diagnostics;
- anticipation effects;
- alternative treatment definitions;
- alternative treatment windows;
- placebo treatment dates;
- placebo outcomes;
- alternative comparison groups;
- staggered-treatment robust estimators;
- matching or reweighting;
- concurrent-policy controls;
- alternative Disclosure Quality Index specifications.

---

## 5. A4 — Financial Transmission Robustness

Potential checks include:

- alternative exposure measures;
- alternative information-quality measures;
- lag structures;
- alternative financial outcomes;
- clustered standard errors;
- high-dimensional fixed effects;
- multicollinearity diagnostics;
- influential observations;
- sector heterogeneity;
- nature-dependence heterogeneity;
- placebo interactions;
- multiple-testing corrections where appropriate.

---

## 6. A5 — Predictive Robustness

Potential checks include:

- temporal holdout;
- rolling validation;
- expanding-window validation;
- sector holdout;
- geographic holdout where feasible;
- model ablation;
- feature-block ablation;
- missing-data sensitivity;
- hyperparameter sensitivity;
- calibration;
- model stability;
- leakage tests;
- interpretable benchmark comparison.

---

## 7. AI Validation

AI-derived measures will not be accepted solely because they are produced by a
high-performing model.

Validation should examine:

- accuracy;
- precision;
- recall;
- F1;
- stability;
- reproducibility;
- human agreement;
- sensitivity to prompts or model specifications where relevant.

---

## 8. Null Results

Null results are treated as substantive evidence.

They may indicate that:

- ESG already captures relevant ecological information;
- reporting regulation changes compliance but not information quality;
- ecological exposure is not priced in the selected financial outcome;
- disclosure quality does not modify financial transmission;
- complex AI architectures do not outperform simpler benchmarks.

The project therefore does not define scientific success as obtaining statistically
significant effects.

---

## 9. Transparency

Where legally and contractually possible, the repository will document:

- model specifications;
- variable definitions;
- robustness decisions;
- benchmark models;
- validation procedures;
- code required to reproduce derived results.
