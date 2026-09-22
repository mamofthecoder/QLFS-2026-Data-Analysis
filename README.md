# South Africa Labour Market Analysis — QLFS 2026 Q1

## Project overview

This project analyses South Africa's Quarterly Labour Force Survey (QLFS) 2026 Q1 microdata, with a focus on **new entrants to unemployment** and how their profile varies by province, gender and education status.

The analysis demonstrates a practical data-analysis workflow using Python and pandas:

- data validation and quality checks
- handling survey-specific missing-value codes
- descriptive statistics
- weighted analysis using the survey `Weight` variable
- groupby/crosstab analysis
- comparison of provincial, gender and education patterns
- visualisation and reporting

## Key findings

The analysis focuses on the share of respondents with a valid unemployment status who were classified as **new entrants**. These are weighted descriptive results, not general unemployment rates.

- **Province:** Limpopo had the highest weighted new-entrant share at **51.12%**, while Western Cape had the lowest at **26.61%** — a difference of **24.51 percentage points**.
- **Gender in Limpopo:** the weighted new-entrant share was **55.27% for females** and **46.49% for males**, a difference of **8.78 percentage points**.
- **Education:** Secondary completed had a weighted new-entrant share of **48.37%**, compared with **35.47%** for Primary completed — a difference of **12.90 percentage points**.

## Important interpretation note

These figures describe the composition of respondents with valid unemployment-status information. They should **not** be interpreted as province-wide unemployment rates or as causal effects of education or gender.

## Repository structure

```text
QLFS-2026-Data-Analysis/
├── README.md
├── notebooks/
├── report/
│   └── QLFS_2026_Q1_New_Entrants_Report.pdf
├── visuals/
│   ├── province.png
│   ├── province_gender.png
│   └── education.png
├── data/
│   └── README.md
└── requirements.txt
```

## Data source

The source is Statistics South Africa's Quarterly Labour Force Survey (QLFS), 2026 Q1. The official QLFS portal provides unit-record data, metadata and survey documentation.

Raw microdata is not included in this public repository. See `data/README.md` for the source and reproducibility notes.

## Tools

- Python
- pandas
- NumPy
- Matplotlib
- ReportLab

## Next steps

A future version can add the cleaned analysis notebook, additional labour-market indicators, and an interactive dashboard.
