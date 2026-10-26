# AI Automation Risk — Workforce Analytics

A Power BI portfolio project exploring AI-automation exposure across 3,000 global roles. The analysis tests whether occupation, geography, or salary best explains the reported risk scores and translates the findings into workforce-upskilling recommendations.

## Project at a glance

- **Tooling:** Microsoft Power BI, DAX, Microsoft Excel
- **Model:** Star schema with a central fact table and Country, Industry, Education, and Company Size dimensions
- **Report:** Interactive KPIs, role-risk ranking, salary-versus-risk scatter plot, geographic view, and industry/country/education slicers
- **Scope:** 3,000 records; descriptive analysis, not a forecast or causal study

## Headline findings reported in the project

- 27% of the 3,000 roles fall in the high-risk band.
- Occupation-level risk ranged from 0.46 to 0.57 in the examples reported, versus 0.48 to 0.53 across countries.
- The report finds no clear salary–risk relationship; Finance is cited as an example of high average pay alongside high risk.
- The report recommends prioritizing upskilling by role rather than by salary band or location.

## Data and method

Dataset. 3,000 global employee records. Primary data is a public Kaggle “AI Impact on Jobs” dataset (role, industry, country, salary, experience, AI-replacement-risk score). A secondary complementary table (training hours, digital-skill level, productivity, innovation) was synthetically generated and is used for method demonstration only — not treated as real-world evidence.
