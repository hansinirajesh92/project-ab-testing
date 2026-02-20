# A/B Testing Case Study

## Overview
A short, end-to-end experimentation case study: define a metric, run an A/B test analysis, and make a decision.

## What’s inside (WIP)
- Data validation + EDA
- Hypothesis test + confidence intervals
- Effect size + practical significance
- Clear decision + recommendation

📓 Notebook: [01_load_and_summary.ipynb](notebooks/01_load_and_summary.ipynb)

## Repo structure
- `notebooks/` - analysis notebooks  
- `src/` - helper code  
- `figures/` - charts for the README  
- `data_sample/` - sample/synthetic data  

## Results
After removing mismatched assignments (control shown new_page or treatment shown old_page), the estimated conversion rates were:

- Control (old_page): **12.04%**
- Treatment (new_page): **11.88%**
- Difference (Treatment - Control): **−0.16 percentage points**

Two-proportion z-test (two-sided):
- **p-value:** 0.1897  
- **95% CI for difference:** [-0.39 pp, +0.08 pp]

**Decision:** No statistically significant improvement from the new page. Recommend keeping the old page (or iterating on the new design and retesting).

