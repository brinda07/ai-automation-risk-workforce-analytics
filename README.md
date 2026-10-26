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

These are findings as stated in the supplied report. Review the Power BI model and source data before reusing or independently presenting the figures.

## Files

- [`report/AI-Automation-Risk-Workforce-Analytics.pdf`](report/AI-Automation-Risk-Workforce-Analytics.pdf) — project summary and reported findings.
- [`powerbi/`](powerbi/) — add the Power BI Desktop `.pbix` project file here. See [`powerbi/README.md`](powerbi/README.md) for upload guidance.
- [`data/README.md`](data/README.md) — data provenance and safe-sharing notes.

## Data and integrity notes

The report describes the primary data as a public Kaggle “AI Impact on Jobs” dataset and says a complementary table (training hours, digital-skill level, productivity, and innovation) was synthetically generated for method demonstration. Those synthetic fields are not real-world evidence. The report also cautions that associations are not causation, the data are cross-sectional, and “demand stays steady” is not a time-series forecast.

Do not commit confidential, personal, licensed, or otherwise restricted data. See [`data/README.md`](data/README.md) before adding any source files. Include dataset attribution and license details if you add data that permits redistribution.

## Adding the `.pbix`

1. Download/clone this repository to your computer.
2. Put the `.pbix` file in the `powerbi/` directory. A suggested filename is `AI-Automation-Risk-Workforce-Analytics.pbix`.
3. Commit and push it using GitHub Desktop or Git. See [`powerbi/README.md`](powerbi/README.md).

GitHub's browser upload is limited to smaller files, and regular Git pushes reject files larger than 100 MB. If the `.pbix` is larger than 100 MB, use Git LFS and check its storage/bandwidth quota before pushing; detailed steps are in the Power BI folder instructions.

## Suggested next steps

- Add the `.pbix` file under `powerbi/`.
- Add a source citation and license link for the exact dataset version used.
- If redistribution is permitted, add data dictionaries or reproducible preparation steps without exposing personal or restricted records.
- Consider adding screenshots of the report pages if you want a quick preview in the repository.

## License

No license has been selected for this repository. Unless a license is added, others do not automatically receive permission to reuse its contents.
