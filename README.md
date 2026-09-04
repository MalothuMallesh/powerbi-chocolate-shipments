#  Power BI Project — Chocolate Shipments Analysis

A Power BI project built on chocolate shipment sales data, covering data prep, modeling, DAX, and report design end-to-end.

## 📊 Report Preview

**Page 1 — Product & Team Performance**
![Product and team breakdown](screenshots/report-page1-product-team.png)

*Sum of amount by product (bar chart) and sum of amount by team (donut chart), with a region slicer on the right.*

**Page 2 — Profit by Geography**
![Total profit by geography](screenshots/report-page2-profit-by-geo.png)

*Total amount, cost, and profit compared across geographies, alongside a product-level profit table with profit % bars.*

**Page 3 — Shipment Count Trend**
![Shipment count trend](screenshots/report-page3-shipment-count-trend.png)

*Shipment count by year and month, with drill-down enabled (year → month) and a team breakdown donut below.*

**Page 4 — Sales Person Breakdown**
![Sales person tables](screenshots/report-page4-sales-person-tables.png)

*Total amount, boxes, and amount-per-box by sales person, plus amount-per-box by sales person × geography, with a date range slicer.*

**Page 5 — Top & Bottom Performers**
![Top and bottom sales persons by profit](screenshots/report-page5-top-bottom-sales-persons.png)

*Top 5 and bottom 5 sales persons by profit, alongside total profit by year and month.*

**Page 6 — Monthly Sales Trend**
![Monthly sales trend](screenshots/report-page6-monthly-sales-trend.png)

*Total shipment amount by month, showing a dip in April 2025 followed by recovery through year-end.*

## 📁 Data

- `data/sample-chocolate-shipments-data-all-Apr-2025.xlsx` — raw shipments dataset used as the source for this report.

## ✅ Topics Covered

**Data Prep & Modeling**
- Data cleaning and adding columns with Power Query
- Data modeling and star schema
- Connecting tables
- Evaluation context
- Working with calendar tables

**DAX**
- Introduction to DAX
- Remixing DAX measures
- Using `VAR` in DAX
- Year-on-year comparisons with DAX

**Report Design & Interactivity**
- Customizing Power BI report interactions
- Visual & report filters
- Using slicers
- Conditional formatting
- Report development — building mockups
- Line charts
- Donut & pie charts
- Top N values with visual filters
- Using pictures (image URLs) in tables
- Table formatting
- Treemap visual
- Customizing tooltips
- KPI card visuals
- Adding images to the report
- Testing the Power BI report

## 🛠 Tools

- Power BI Desktop / Power BI Service
- Power Query (M)
- DAX
