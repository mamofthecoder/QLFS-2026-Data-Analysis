---
title: South Africa Labour Market Analysis — QLFS 2026 Q1
---

# South Africa Labour Market Analysis

## QLFS 2026 Q1 — New Entrants to Unemployment

**Python • pandas • NumPy • Matplotlib • Survey-weighted analysis**

This project analyses Statistics South Africa's **Quarterly Labour Force Survey (QLFS) 2026 Q1**, focusing on how the weighted share of new entrants to unemployment varies by **province, gender, and education status**.

[**View the analysis notebook**](notebooks/QLFS_2026_Analysis_Portfolio.ipynb) · [**View the full PDF report**](report/QLFS_2026_Q1_New_Entrants_Report.pdf)

---

## Project Overview

The analysis follows an end-to-end workflow:

**Understand → Validate → Clean → Explore → Analyse → Visualise → Report**

The original dataset contains approximately **62,819 observations and 200 variables**. The project includes data validation, treatment of special missing/not-applicable values, exploratory analysis, survey-weighted calculations, visualisation, and interpretation.

The raw QLFS microdata is not included in this public repository.

---

## Key Findings

### 51.12% — Limpopo

Among respondents with a valid unemployment status, Limpopo had a **51.12% weighted new-entrant share**, compared with **26.61% in the Western Cape**.

**Difference: 24.51 percentage points**

![Weighted new-entrant share by province](visuals/province.png)

### 8.78 pp — Gender difference in Limpopo

In Limpopo, the weighted new-entrant share was:

- **Female: 55.27%**
- **Male: 46.49%**

The female-minus-male difference was **8.78 percentage points**.

![Weighted new-entrant share by province and gender](visuals/province_gender.png)

### 48.37% — Secondary completed

The weighted new-entrant share for respondents with **secondary education completed** was **48.37%**, compared with **35.47%** for respondents with **primary education completed**.

**Difference: 12.90 percentage points**

![Weighted new-entrant share by education status](visuals/education.png)

---

## Research Questions

1. How does the weighted new-entrant share vary across South African provinces?
2. How does the weighted new-entrant share differ between males and females across provinces?
3. How does the weighted new-entrant share vary across education statuses?

---

## Methodology

The main findings use the QLFS survey **Weight** variable.

For new-entrant calculations, the denominator is restricted to respondents with a **valid unemployment status**. The percentages therefore describe the weighted share of that group classified as new entrants.

These figures are **not general-population unemployment rates**, and the analysis is descriptive rather than causal.

---

## Skills Demonstrated

**Python** · **pandas** · **NumPy** · **Matplotlib** · **Data Cleaning** · **Data Validation** · **Exploratory Data Analysis** · **Survey Weighting** · **GroupBy & Aggregation** · **Data Visualisation** · **Analytical Reporting**

---

## Explore the Full Project

For the complete code and analytical process:

[**Open the Jupyter Notebook →**](notebooks/QLFS_2026_Analysis_Portfolio.ipynb)

For the polished written analysis:

[**Open the PDF Report →**](report/QLFS_2026_Q1_New_Entrants_Report.pdf)

For project documentation, reproducibility instructions, and limitations:

[**View the repository README →**](README.md)

---

*Portfolio data-analysis project using Statistics South Africa QLFS 2026 Q1.*
