# Excel Analytics Dashboard — Superstore Sales

**Author:** Evan Pritchard · [epritch.github.io](https://epritch.github.io) · [LinkedIn](https://www.linkedin.com/in/evan-pritchard-9a0922168/)

A professional Excel workbook demonstrating data analysis skills including PivotTable-style
summaries, Power Query transformation documentation, conditional formatting, embedded charts,
and Excel formula modeling — all applied to the public Tableau Superstore dataset.

---

## Workbook Structure

| Sheet | Contents |
|-------|----------|
| **Raw Data** | 20-row representative transaction sample, formatted as a structured table |
| **Pivot Summary** | KPI cards, category × region revenue pivot, profitability analysis with conditional formatting |
| **Charts & Trends** | Line chart (monthly trend), clustered bar (regional comparison), donut (category share) |
| **Power Query Reference** | Step-by-step M language transformation log with sample code |

---

## Skills Demonstrated

**Data Preparation**
- Structured table formatting with alternating row styles
- Proper number formatting (`$#,##0`, `0.0%`, `#,##0`)
- Power Query transformation pipeline (10 documented steps)

**Analysis**
- PivotTable-equivalent summaries using Excel formulas (`SUM`, `AVERAGE`)
- Dynamic margin calculation: `=C16/B16` (avoids hardcoding)
- Revenue per order: `=B16/E16`
- Grand total row using range formulas

**Visualization**
- Line chart: 3-series monthly revenue trend by category
- Clustered bar: Revenue vs Profit by region
- Donut/Pie: Category revenue share

**Conditional Formatting**
- 3-color scale on profit margin column (red → amber → green)
- Highlights underperforming categories automatically

---

## Key Insights (from Pivot Summary)

- **Technology** has the highest revenue ($836K) and best margin (17.4%)
- **Furniture** has the worst margin (2.5%) despite $742K in revenue — a cost/discount issue
- **West region** leads all four regions in both revenue ($725K) and profit
- Conditional formatting immediately flags Furniture's margin as the outlier

---

## Tools Used

- Microsoft Excel / openpyxl (Python library for programmatic generation)
- Data: [Tableau Superstore Dataset](https://public.tableau.com/app/learn/sample-data) (public domain)

---

## Files

```
excel-dashboard/
└── Superstore_Dashboard_EvanPritchard.xlsx   # 4-sheet workbook
```

---

*Part of my data analytics portfolio.*
*See also: [BI Dashboard](https://epritch.github.io/bi-dashboard/) · [SQL Case Study](https://github.com/epritch/sql-case-study)*
