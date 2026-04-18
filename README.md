# PRODIGY_DS_01 — World Population Distribution Analysis

## Task Overview
Visualizing the distribution of a continuous/categorical variable using
bar charts and histograms — part of my Data Science Internship at Prodigy InfoTech.

## Dataset
- **Source:** World Bank Open Data
- **Indicator:** SP.POP.TOTL (Total Population)
- **File:** API_SP.POP.TOTL_DS2_en_csv_v2_38144.csv
- **Coverage:** 215 countries | 1960–2023

## What I Built
4 visualizations in one figure:
1. **Top 15 Most Populous Countries** — horizontal bar chart (2023)
2. **Histogram** — distribution of country populations by size bracket
3. **World Population Growth** — line chart from 1960 to 2023
4. **Population by Region** — Asia, Africa, Europe, Americas, Oceania

## Key Insights
- India (1.44B) surpassed China (1.41B) as the most populous country in 2023
- 62 countries fall in the 10–50M range — the most common population band
- 57 countries have fewer than 1 million people
- World population grew from 3B (1960) to 7.95B (2023)
- Asia holds over 59% of the global population

## Tools & Libraries
- Python 3
- Pandas
- Matplotlib
- NumPy

## Files
| File | Description |
|------|-------------|
| `task01_visualization.py` | Main Python script |
| `API_SP.POP.TOTL_DS2_en_csv_v2_38144.csv` | Dataset |
| `world_population_analysis.png` | Output chart |

## How to Run
```bash
