# E-Commerce Sales Analysis Dashboard | Power BI

## Project Overview
This project is an interactive E-Commerce Sales Analysis report built in Microsoft Power BI. The supplied `.pbix` report contains four pages: **Home Page**, **Country Level Performance**, **Product level Performance**, and **_Tooltip**.

The report is designed to summarize sales and invoice activity, provide time-based analysis, and allow users to explore country/region and product performance.

## Dashboard Preview
![E-Commerce Sales Analysis Dashboard](https://github.com/Mala-chetan/E-commerce-Sales-Analysis/blob/main/Screenshot%202026-10-18%20234848.png)

## Dashboard Pages and Visuals

### 1. Home Page
- KPI cards for latest-month Sales, Invoices, Quantity, and Stocks.
- Month-based trend visual, labelled around invoice trends.
- Weekday/date matrix or heatmap.
- Horizontal bar visual.
- Country/Region slicer.
- KPI selection control that includes Sales, Invoices, Quantity, and Stocks.

### 2. Country Level Performance
- Map visual using country-level information.
- Country/region filter.
- Summary table with country, region, sales, invoices, cancelled invoice percentage, and contribution metrics.
- Bar visual using sales/invoice/customer/stock-related measures.

### 3. Product Level Performance
- Scatter visual with product/category and sales/quantity/invoice measures.
- Product summary table with category, description, stock code, sales, invoices, and cancelled invoice percentage.
- Country/region filter.

### 4. Tooltip
- Tooltip page with invoice/time grouping and sales/invoice summary details.

## KPIs and Measures Identified in the Report
The Power BI report contains measure names including:
- `Total Sales`
- `Total Invoices`
- `Total Quantity`
- `Total Stocks`
- `Latest Month Sales`
- `Latest Month Invoices`
- `Latest Month Quantity`
- `Latest Month Stocks`
- `MoM Sales %`
- `MoM Invoices %`
- `MoM Quantity %`
- `MoM Stocks %`
- `Cancelled Invoices %`
- `% contribution`
- `Total Customers`

The exact DAX definitions and business interpretation should be reviewed in Power BI Desktop before publishing numerical findings.

## Tools
- Microsoft Power BI Desktop
- DAX measures and report-level filtering
- Power BI map, card, line, matrix/table, bar, scatter, and slicer visuals

## How to View the Project
1. Download or clone this repository.
2. Open `powerbi/Ecommerce_Sales_Report.pbix` in Power BI Desktop.
3. If prompted, review the data source or sign in to the required Power BI service.
4. Inspect each report page and verify that visuals load correctly.
5. See `documentation/dashboard_analysis.md` for the visual inventory and validation checklist.

## Data and Reproducibility Notes
- The screenshot and PBIX report were supplied for this project, but the separate source dataset and complete source schema were not supplied.
- Add the source dataset only if you have permission to redistribute it and it contains no confidential or personal information.
- Never commit passwords, credentials, tokens, or private customer data.

## Business Questions
- What are the latest-month sales, invoice, quantity, and stock values?
- How do sales and invoices change over time?
- Which countries or regions contribute the most sales?
- Which products or categories contribute the most sales and quantity?
- What percentage of invoices are cancelled?
- How does filtering by country or region change the reported KPIs?
