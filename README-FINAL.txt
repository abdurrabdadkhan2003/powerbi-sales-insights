# Power BI Sales Insights – Full Project Documentation

This project is a full Sales Insights analysis in Power BI, built end-to-end covering ETL, data modeling, dashboarding, stakeholder feedback, and reporting.

## Project Overview
- Analyze sales transactions from a retail company: markets, customers, products, and time periods.
- Focus on revenue, sales quantity, profit margin, and performance analysis.

## Workflow
- Imported raw data into MySQL and connected Power BI using ODBC.
- Performed ETL and data cleaning: handled currency normalization (INR, USD), removed duplicates, fixed data types.
- Built initial Power BI data model and table relationships.
- Developed interactive dashboards for:
  - Total revenue & sales metrics
  - Revenue and profit breakdown by market, customer, and product
  - Sales trend analysis across years (2017-2020)
  - Performance visualizations (profit margin %, contribution %, dynamic alerts)
- Verified dashboard accuracy by cross-checking SQL results and Power BI visuals.

## Stakeholder Feedback & Changes
- Documented change requests and requirements from manager (see `feedback/WhatsApp-Image-...`).
- Incorporated feedback to:
  - Use normalized sales amount in all visuals
  - Flag declining sales and propose fixes
  - Add customer/product level margin/cost analysis
  - Create sales split between brick-and-mortar vs. ecommerce
  - Add conditional color coding and new insight measures

## Key Files & Screenshots
- `sales-insights.pbix` – Power BI dashboard file
- `screenshots/Key-Insights.jpg` – Key metrics visuals
- `screenshots/Profit-Analysis.jpg` – Profit breakdowns
- `screenshots/Performance-Inisights.jpg` – Performance alert visuals
- `feedback/WhatsApp-Image-...` – Manager’s feedback/request (for traceability)
- Additional ETL documentation, verification screenshots included

## How to Use / Reproduce
- Restore the MySQL dump and connect to Power BI using ODBC
- Follow the ETL/data prep in Power BI as shown in screenshots and .pbix
- Review stakeholder feedback and update dashboard per provided requirements
- Reference progress log/commits for incremental steps

---

## Progress Log
- [1]: Initial ETL, currency normalization
- [2]: Built core Power BI data model
- [3]: Added reporting measures and visuals
- [4]: Incorporated manager feedback and enhanced dashboard

---

**For full details, see screenshots, .pbix file, and feedback history.**
