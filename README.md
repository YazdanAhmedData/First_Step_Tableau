# 📊 Sales Performance Dashboard | Tableau

<img width="100%" alt="Sales performance Tableau dashboard screenshot" src="https://github.com/user-attachments/assets/c0bc287a-a2eb-47ae-a3b1-89a4b3717c01" />

**Portfolio project · Foundational business intelligence · Sales and returns**

## Executive Summary
This foundational Tableau project explores order and sales data across 2015, 2016 and 2017, alongside manager and returns datasets. It demonstrates the first steps of turning operational sales records into a visual reporting experience.

## Business Problem
Sales teams need to track performance over time and understand whether results differ across managers or return activity. A dashboard helps stakeholders inspect changes, compare groups and decide where a deeper investigation is needed.

This project is intentionally positioned as an early Tableau project in the portfolio; later SQL and customer analytics projects demonstrate deeper analysis.

## Business Questions
- How does sales activity change across the available years?
- Which managers or groups differ on the dashboard's sales measures?
- What return patterns appear in the available records?
- Which filters and visual views help users investigate a change in performance?
- What definitions or data fields would be needed for a more complete sales-performance review?

## KPI Framework
Use the exact fields and calculations in the workbook when reporting final values.

| KPI | Suggested definition | Business use |
|---|---|---|
| Sales | Sum of the selected sales/revenue field | Overall performance |
| Orders | Distinct order IDs | Transaction volume |
| Average order value | Sales ÷ distinct orders | Average transaction value |
| Return count / return rate | Returned orders ÷ eligible orders, if IDs can be matched | Monitor returns |
| Year-over-year change | (Current year − prior year) ÷ prior year | Compare periods |
| Manager-level performance | Sales/orders by manager using a consistent mapping | Review distribution and follow-up needs |

## Insights & Decision Use
- **Trend review:** identify periods where sales rise or fall and investigate the business context before assigning a cause.
- **Manager comparisons:** compare results using the same date range and metric definitions.
- **Returns analysis:** inspect returned orders and verify how the returns table links to orders; avoid counting duplicated join rows.
- **Dashboard design:** filters should help a stakeholder move from a high-level KPI to a specific year, manager or return pattern.

The repository should not claim a particular best-performing manager or sales increase without a validated number from the workbook.

## Data & Repository Contents
| File | Purpose |
|---|---|
| `FirstStep.twbx` | Packaged Tableau workbook |
| `Orders 2015.csv` | 2015 order records |
| `Orders 2016.csv` | 2016 order records |
| `Order 2017.csv` | 2017 order records |
| `Managers.csv` | Manager reference data |
| `Returns.csv` | Returns data |

## How to Explore
1. Open `FirstStep.twbx` in Tableau Desktop.
2. Review the dashboard screenshot and filters.
3. Inspect the source data to understand how orders, managers and returns are related.
4. Validate calculated fields, date filters and join keys before quoting a KPI.

## Limitations & Next Steps
- Confirm whether the years are comparable in coverage and data quality.
- Document sales field definitions, order grain and return matching logic.
- Add verified headline findings with dates, denominators and implications.
- Add a short data dictionary and a more advanced drill-down or trend analysis.

## Skills Demonstrated
Tableau · Dashboard design · Sales reporting · Time-series exploration · Returns analysis · KPI framing · Data visualisation

## Author
**Yazdan Ahmed** · [GitHub Portfolio](https://github.com/YazdanAhmedData)
