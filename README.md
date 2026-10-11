# Savings retention case study

Analysis of what drives customers to retain or close a fixed-rate savings
bond at maturity, plus an outline of how I'd build a model to forecast it.

Private repo. The data is a case study dataset shared for interview purposes only.

## Structure
- `data/` – case study workbook (2,000 maturing accounts, Aug 2023 – Jun 2026)
- `notebooks/` – analysis, one notebook per step
- `outputs/tables/` – summary tables (Excel)
- `outputs/charts/` – charts used in the presentation
- `notes/decisions.md` – every decision made along the way and why

## Tools
Python (pandas, matplotlib, statsmodels) for the analysis.
Key tables exported to Excel so they can be checked and reproduced as pivots.