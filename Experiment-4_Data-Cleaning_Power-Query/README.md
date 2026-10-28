# Experiment 4: Data Cleaning with Power Query (Cafe Sales)

**Files:** `BA_exp4.pdf` (report), `DATACLEANING.pbix` (Power BI file)

## Business question
A cafe's transaction data contains missing values, duplicate Transaction IDs and invalid placeholder text. How can it be cleaned in a repeatable way so it is ready for analysis?

## Data
Kaggle dataset "Cafe Sales - Dirty Data for Cleaning Training" (`dirty_cafe_sales.csv`), 1,000+ transaction rows with columns such as Transaction ID, Item, Quantity, Price Per Unit, Total Spent, Payment Method, Location and Transaction Date.

## Cleaning steps
1. Profiled columns with Column Quality, Column Distribution and Column Profile.
2. Replaced the placeholder values "ERROR" and "UNKNOWN" with null.
3. Handled missing values in Item, Payment Method and Location.
4. Corrected data types (numeric, date, text).
5. Rebuilt Total Spent as Quantity x Price Per Unit, flagging rows where either input was null.
6. Removed duplicate rows by Transaction ID.
7. Checked the Applied Steps list so the process can be repeated.

## Tools
Power BI Desktop, Power Query
