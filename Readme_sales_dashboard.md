# Project: Sales Dashboard (Power BI) — Week 1
**Folder:** Week01/Power_BI
**Author:** Hitesh Garg
**Date:** 05-Nov-2025

> **Objective:** Build an interactive Power BI dashboard integrating Excel data to analyze regional and product-wise sales trends.  
> **Outcome:** Delivered a visually rich, refreshable dashboard showing KPIs, sales trends, and slicer-based insights.

## Files (canonical)
- `sales_dashboard_v1.pbix` — Power BI Desktop file (open in Power BI Desktop).
- `sales_dashboard_v1.pdf` — Exported PDF snapshot for portfolio/presentation.
- `sales_dashboard_steps_v1.md` — Power Query & transformation log (this file).
- `excel_practice_pivot_v1.xlsx` — Cleaned Excel dataset used as PBIX data source.
- `desc.md` — Short project description/image.

## How to open
1. Open `sales_dashboard_v1.pbix` in Power BI Desktop.
2. If visuals are blank or values do not match:
   - Home → Transform data → Data source settings → point to `excel_practice_pivot_v1.xlsx`.
   - Then Home → Refresh.
3. To view static snapshot, open `sales_dashboard_v1.pdf`.

## Short description
Interactive dashboard showing:
- Total Sales, Total Units, Avg Sales per Unit (KPI cards)
- Sales by Region (bar)
- Sales by Product (column)
- Sales Trend over Time (line)
Includes slicers for Region and Product.

**Key Metrics Displayed:** Total Sales, Total Units Sold, Avg Sales per Unit  
**Filters Available:** Region, Product, Sales Level

## Data lineage & key steps
See `sales_dashboard_steps_v1.md` for a step-by-step record of transformations and measures.

## Notes / Known issues
- PBIX links to the local Excel workbook. If file is moved, relink using Data Source settings.
- For sharing on GitHub, the PBIX is included but large. Consider publishing the PDF + step file and keeping PBIX in `BACKUPS/` if file-size becomes an issue.
