\# Dual Burden: Diabetes and Depression



\## Business Question

Does comorbid depression/anxiety in adults with type 2 diabetes associate with worse glycemic control (HbA1c) and higher healthcare utilization — a proxy for cost burden — compared to adults with diabetes alone?



\## Why This Matters

Depression and type 2 diabetes frequently co-occur, and each condition can worsen the other — poor mental health is linked to reduced self-management (diet, medication adherence, activity), while chronic disease burden itself elevates depression risk. This "dual burden" is associated with worse clinical outcomes and higher healthcare utilization, yet mental health screening is not consistently integrated into diabetes care pathways. Quantifying this relationship using population-level data helps make the case for integrated screening and care models — and for understanding where the cost burden of untreated comorbidity actually falls.



\## Data Source

National Health and Nutrition Examination Survey (NHANES), U.S. Centers for Disease Control and Prevention (CDC) — publicly available, nationally representative health survey data.



\*\*Note on cost data:\*\* NHANES does not collect direct healthcare expenditure ($) data — it is a health examination survey, not a claims/billing survey. Instead, this project uses NHANES' healthcare \*\*utilization\*\* variables (doctor visits, ER visits, overnight hospitalizations in the past 12 months) as a utilization-based proxy, and translates group differences into an estimated cost impact using \*\*published, cited average unit costs\*\* (e.g., average cost per ER visit, per hospitalization) from peer-reviewed or government sources. This is not a direct expenditure analysis — a natural next step would be linking to the Medical Expenditure Panel Survey (MEPS), which does capture direct dollar costs.



\## Status

🚧 In progress — data pull and cohort definition underway.



\## Methods (planned)

\- Data pull: Python (Google Colab)

\- Cohort definition \& cleaning: SQL (BigQuery)

\- Visualization: Power BI

\- Analysis: group comparisons of HbA1c and healthcare utilization by comorbidity status; utilization translated to an estimated cost impact using cited published unit costs



\## Limitations (to be expanded)

\- Cross-sectional survey data — findings will describe association, not causation.

\- Cost impact is estimated from utilization × published unit costs, not observed expenditure data — treat as a directional estimate, not a precise dollar figure.

