# Superstore Sales Analysis | Excel Dashboard

## Overview
An end-to-end retail analytics project built in Microsoft Excel to evaluate sales performance, profitability, product mix, customer segments, regional performance, and shipping efficiency.

## Business Questions
- How are sales and profit trending over time?
- Which categories, sub-categories, and products drive or erode profit?
- Which regions and customer segments contribute most to revenue?
- How efficient are the available shipping modes?
- Where should management investigate loss-making transactions?

## Dataset
- **Valid transaction rows:** 9,994
- **Unique orders:** 5,009
- **Unique customers:** 793
- **Date coverage:** 2014-01-03 to 2017-12-30
- **Measures:** Sales, Profit, Quantity, Discount, and derived Shipping Days

## Headline KPIs
| KPI | Result |
|---|---:|
| Total Sales | $2,297,200.86 |
| Total Profit | $286,397.02 |
| Orders | 5,009 |
| Customers | 793 |
| Units Sold | 37,873 |
| Profit Margin | 12.47% |
| Average Order Value | $458.61 |

## Workbook Contents
1. **Executive Dashboard** — KPI cards, monthly sales trend, category and regional comparisons, and executive takeaways.
2. **Clean Data** — filterable Excel Table containing the valid transaction records.
3. **Analysis** — monthly, category, regional, sub-category, segment, shipping, and product-level summaries.
4. **Data Quality** — row validation, duplicate checks, missing-value checks, and documented treatment.
5. **README** — project objectives, methodology, limitations, and workbook guide.

## Data Preparation & Methodology
- Removed two fully blank trailing rows and four unnamed empty columns.
- Retained all 9,994 valid transaction records.
- Checked exact duplicate rows and missing values in key fields.
- Retained negative-profit transactions because they represent genuine loss-making sales.
- Derived **Shipping Days = Ship Date − Order Date**.
- Aggregated sales, profit, quantity, and order counts by business dimensions.

## Tools & Skills
**Microsoft Excel · Data Cleaning · Pivot-Style Analysis · KPI Development · Charts · Business Intelligence · Data Storytelling**

## Key Analytical Note
This is a descriptive analysis of a historical training dataset. Findings indicate patterns and areas for investigation; they do not prove causation or represent live business performance.

## Files
- `Superstore_Sales_Analysis_10of10.xlsx` — complete Excel project.
- `README.md` — project documentation.

---
*Created as a data analytics portfolio project.*
