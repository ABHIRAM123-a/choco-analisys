# choco-analisys
### Project Title / Headline

🍫 Chocolate Sales & Shipments Analytics Dashboard

An interactive Power BI dashboard that analyzes chocolate shipment performance across products, sales teams, geographies, and time. It tracks revenue, profit, boxes shipped, and shipment volume, with year-over-year comparisons and drill-through analysis.

### Short Description / Purpose

The Chocolate Sales & Shipments Analytics Dashboard is a business intelligence solution built in Power BI to analyze sales and shipment data for a chocolate company. It consolidates revenue, profit %, boxes shipped, and shipment counts into one view. It also compares current-year and previous-year performance. This helps users spot top products, strong regions, high-performing sales people, and seasonal trends.

### Tech Stack
📊 Power BI Desktop: dashboard development and interactive visualization.
📂 Power Query: data import, cleaning, and transformation.
🧠 DAX (Data Analysis Expressions): custom measures such as Total Amount, Total Profit, Profit %, Total Boxes, Shipment Count, Previous-Year (PY) values, and 12-month variance.
🗃️ Data Modeling: star-schema model with a shipments fact table linked to products, people, locations, and a calendar date table.
📈 Data Visualization: KPI cards, line, donut, pie, column, treemap, and clustered column charts, tables with conditional formatting, and slicers.
🔍 Drill-through and Navigation: a drill-through detail page with a back button, plus a custom background and icons for a polished look.
📁 File Format: .pbix
### Data Source

Source: Chocolate sales and shipments dataset

The data is organized into five tables:

Table	Purpose
shipments	Amount, boxes shipped, and shipment-level records
products	Product names and product-level details
people	Sales team members (first name, team, picture)
locations	Geography/region of each sale
calendar	Date table for time intelligence (month, year, month name)

Key fields analyzed: Product, Team, Sales Person, Geo, Amount, Boxes, Profit %, Shipment Count, Date.

### Features / Highlights
• Business Problem

Sales and shipment data is spread across products, people, regions, and dates, so it is hard to see which products earn the most profit, which regions and sales people perform best, and how this year compares with last year. Key questions include:

Which products generate the most revenue and profit?
Which geographies contribute the most to sales?
Which sales people and teams perform best?
How do sales and boxes shipped compare with the previous year?
How are shipment sizes distributed?
Which months show growth or decline?
• Goal of the Dashboard
Monitor key KPIs (amount, profit, boxes, shipments) at a glance.
Compare products, regions, and sales people.
Track year-over-year performance using previous-year and 12-month variance measures.
Filter by date range and geography.
Drill into product-level profit details.
Support data-driven decisions on product mix, regional strategy, and team performance.
• Walkthrough of Key Visuals

📌 KPI Cards: Total Amount, Total Profit, Profit %, Total Boxes, and Shipment Count, each with a custom icon.

📌 Amount vs. Previous Year, Line Chart: monthly sales for the current year against the previous year, with a dashed comparison line and 12-month variance in the tooltip.

📌 Boxes: Previous Year vs. Current Year, Line Chart: the same comparison for shipment volume.

📌 Top 6 Products, Treemap: the six products with the highest total amount.

📌 Amount by Geography, Donut Chart: each region's share of total sales.

📌 Shipment Distribution, Clustered Column Chart: shipment counts by boxes-shipped bins, showing typical order sizes.

📌 Product Performance Table: total amount and profit % per product, with color-coded conditional formatting (green for strong, red for weak).

📌 Sales People Performance Table: total amount, profit %, total boxes, and each person's photo, with data-bar and icon indicators.

📌 Sales by Team, Pie Chart: sales contribution by team.

📌 Drill-through Page: a detail page showing product-level amount and profit %, reached from the main dashboard and returnable via a back button.

📌 Interactive Slicers: a date-range slicer (Between) and a geography slicer to filter every visual at once.


