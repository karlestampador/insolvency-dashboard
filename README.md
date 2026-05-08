# Canadian Insolvency & Macroeconomic Stress Dashboard

## What This Project Does
I'm trying to answer the question: "When do Canadian businesses and households become insolvent, and what macroeconomic conditions predict stress spikes?"

One-paragraph plain-language summary: what question it answers, what data it uses, 
what the dashboard shows. Write for a credit risk analyst, not an academic reviewer.

## Key Findings
- 3 bullet points of your strongest empirical findings. 
  Example: "Consumer insolvency filings show peak correlation with BoC rate changes 
  at a 4–5 quarter lag, consistent with the transmission timeline of variable-rate 
  mortgage repricing."

## Dashboard
[Live Dashboard Link — Power BI Service]
[Screenshot of each page]

## Data Sources
Table: 
Source | Coverage | Granularity | URL 
|----|------|-------|-----|
OSB | Hi | Hi | Link

## Technical Stack
DuckDB · Python (Pandas, Plotly) · Power BI · GitHub

## Repository Structure
[Your folder tree]

## Methodology Notes
- Fiscal year vs. calendar year alignment decision
- COVID period exclusion from lag analysis
- Province code standardization approach
- Monthly-to-quarterly aggregation method

## How to Reproduce
Step-by-step instructions to run cleaning notebooks and SQL pipeline from scratch.

### Requirements
Run this beforehand to ensure all packages are met:
```bash
pip install duckdb pandas plotly jupyter openpyxl requests stats_can
```
