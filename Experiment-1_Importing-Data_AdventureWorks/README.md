# Experiment 1: Importing Data into Power BI (AdventureWorks)

**Files:** `AARUSH_BA.pdf` (report), `Bussiness analytics.pbix` (Power BI file)

## Business question
Sales, customer and product data arrive as separate flat files. How can they be combined into one data model and a single reporting dashboard?

## Data
AdventureWorks CSV files, as described in the report:
- Sales Data 2022: 29,481 order lines (1 Jan to 30 Jun 2022, 11,839 orders, 102 products)
- Customer Lookup: 18,154 customers
- Product Lookup: 293 products

## What was done
- Imported the three CSV files with Get Data, then reviewed and corrected data types in Power Query.
- Created one-to-many relationships on ProductKey and CustomerKey.
- Built a one-page dashboard using the Sum of OrderQuantity aggregation (no custom DAX measures).

## Dashboard visuals
KPI card (Total Quantity Sold), clustered bar chart (quantity by product), line chart (trend over time), donut chart and scatter chart. See the PDF for the full list and screenshots.

## Tools
Power BI Desktop, Power Query
