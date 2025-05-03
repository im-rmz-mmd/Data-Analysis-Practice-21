# Hospital Patient Experience Dashboard (Power BI)

This dashboard analyzes U.S. hospital performance using **HCAHPS survey data** — a national standard for measuring patient experience. It offers actionable insights for healthcare providers, administrators, and data analysts.

## Overview

The dashboard focuses on **Top-box percentages** (highest satisfaction scores) across 10 key measures, and tracks both **temporal** and **geographic** variations.

### Key Features:
- **KPI Cards** for:
  - Total Measures
  - Avg. Top-box % (National & State)
  - Overall Response Rate

- **Bar Chart**:  
  - Top-box % by Measure (descending)
  
- **Stacked Bar Chart**:  
  - Top / Middle / Bottom responses for each measure

- **Map Visualization**:  
  - Avg. Top-box % by State

- **Line Chart**:  
  - Trend of Avg. Top-box % over release periods

- **Treemap**:  
  - Measures grouped by type (Composite, Global, Individual)

---

## Dataset

- Source: HCAHPS Patient Survey (CMS)
- Structure: 10 measures across U.S. states and years
- Preprocessing: Power Query
- Metrics: Top-box %, response rate, state/national comparison

## Tools Used

- Power BI Desktop
- DAX (Calculated measures)
- Power Query (ETL)

---

## Use Cases

- Identify **low-performing areas** in patient care
- Track **improvements or declines** over time
- Compare **regional performance**
- Support **data-driven decision making** in hospitals
