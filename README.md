# Task 5 – Excel Data Analysis

**Dataset:** Superstore-style retail sales (600 orders, Jan–Dec 2025).
**Workbook:** `Task5_Excel_Data_Analysis.xlsx`

| Tab | Purpose |
|---|---|
| Summary | KPIs, 3 charts, one-paragraph key findings |
| Working | SUMIFS / COUNTIFS / AVERAGEIFS formulas: KPIs + 5 pivot-style tables (Category, Region, Segment, Monthly trend, Category×Region) |
| Raw_Data | Untouched source data, frozen header, filters, named ranges |

**Approach:** Named ranges (Sales, Profit, Region, ...) -> SUMIFS-based analysis -> charts -> findings.

**Key findings:** Total sales ~406.6K, profit ~17.5K (4.3% margin). Technology most profitable (14%), Furniture loss-making (-11.1%) due to discounts, Central region break-even, Nov–Dec peak season.

**Interview answers**
- *SUMIFS vs PivotTable:* SUMIFS for fixed, formula-driven report cells that must feed dashboards; PivotTable for quick exploration/slicing.
- *Keep pivot source live:* Convert data to an Excel Table (Ctrl+T) or use a dynamic named range, then Refresh All.
- *Retail KPI:* Profit margin (shows if growth is actually profitable); also AOV and sales growth MoM.
