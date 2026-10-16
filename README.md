# Inventory-Retail-Stocks-Analysis-PowerBi
   Inventory Retail Stocks Analysis
                     Excel and Power BI Mini Project Report
                                                              Analysis period: 08 Oct 2024 – 08 Oct 2026


1. Project Overview
This project analyses retail sales transactions using Microsoft Excel and Power BI. The supplied cleaned dataset contains 1,000 transaction records across 4 product categories, 14 products, 4 regions and 20 stores. The dataset covers 08 October 2024 to 08 October 2026. The analysis focuses on sales performance, product/category contribution, regional and store performance, quantity sold, discount patterns, payment methods, and the supplied stock classification.
2. Project Objectives
•	Analyze total sales and order activity across the available reporting period.
•	Compare sales performance by region, store, product, and product category.
•	Understand quantity sold, average transaction value, and discount patterns.
•	Compare payment-method usage and sales contribution.
•	Review the supplied High Stock, Medium Stock & Low Stock classification alongside sales performance.
•	Build an interactive Power BI report with KPIs, trend visuals, and slicers for business exploration.
3. Data Source and Dataset Attributes
Data Source Description: Google Data Search Portal & Inventory Stock Analysis OCT 2024 to OCT 2026. The workbook also includes raw data, formatting, sorting/filtering, Pivot Tables, dashboard, and Excel Report sheets.

Attribute	Data Type	Description
Order ID	Text	Unique transaction/order identifier
Order Date	Date	Date the order was placed
Customer Name	Text	Customer associated with the order
Region	Text	Sales region: North, South, East, or West
Store	Text	Store identifier
Product	Text	Product name
Category	Text	Product category
Quantity	Whole Number	Units recorded for the transaction
Unit Price	Fixed Decimal	Price per unit
Discount (%)	Whole Number	Discount percentage recorded
Total Amount	Fixed Decimal	Recorded sales amount for the transaction
Payment Method	Text	Payment method used
Stock Details	Text	Provided stock classification: High Stock , Medium Stock or Low Stock

4. Problem Statement
•	Retail businesses generate large volumes of sales data across different products, categories, stores, regions, and payment methods. 
•	Analysing this data manually can make it difficult to identify sales trends, understand product performance, compare regional sales, and monitor business performance.
•	The objective of this project is to analyse retail sales data using Microsoft Excel and Power BI to transform raw sales data into meaningful business insights. 
•	Excel is used for data cleaning, preprocessing, sorting, filtering, and Pivot Table analysis. Power BI is used for data modelling, DAX calculations, interactive dashboards, and visualisations.
•	The analysis focuses on identifying top-performing products and categories, comparing sales across regions and stores, evaluating order quantities and average order value, analysing monthly sales trends, and understanding customer payment preferences. 
•	The project aims to help businesses identify areas for improvement, make informed decisions, and develop effective sales strategies to improve overall performance.

5. Tools and Technologies
•	Microsoft Excel: used for reviewing raw data, standardizing formats, sorting/filtering, cleaning, and summarizing sales through Pivot Tables and dashboard/report sheets.
•	Microsoft Power BI: intended for data modelling, DAX measures, interactive visualizations, KPI cards, and slicers. The supplied PBIX file is included as the Power BI project artifact.
6. Data Preprocessing and Quality Checks
•	Used the “Cleaned Dataset” sheet as the analysis table with 1,000 rows and 13 columns.
•	Checked missing values: 0 blank cells were found in the selected cleaned dataset.
•	Checked duplicate rows: 0 duplicate full rows were found.
•	Checked order identifiers: 0 repeated Order ID values were found.
•	Confirmed Order Date is interpreted as a date field and numeric fields are available for aggregation.
•	Recommended keeping the raw-data sheet unchanged and using the cleaned dataset for reporting; validate any business rules for discounts and Total Amount before final publication



7. Key Performance Indicators (KPIs)
KPI	Value
Total Sales	6,164,336.32
Number of Orders	1,000
Total Quantity Sold	25,581
Average Sales per Order	6,164.34
Average Recorded Discount	6.7%
Reporting Period	08 Oct 2024 – 08 Oct 2026

8. Data Modelling (Calculated Columns and DAX Measures)
In Data Modelling, Product Table was Created and linked to the main dataset by using Product column and Visualization shown below,

 

Using DAX (Data Analysis Expression), Calculated Columns and Measures were created to enhance analytical insights.
•	Calculated Columns:
•	Stock Details


•	Measures:
•	Total Sales
•	Total Order Counts
•	Total Quantity
•	Average Orders

9.Analysis and Visualizations
•	KPI cards — Total Sales, Order Count, Total Quantity, and Average Order Value.
•	Line chart — Monthly sales trend using Order Date and Total Amount.
•	Pie chart — Sales by Region and Total sales to compare performance.
•	Clustered Bar Chart — Sales by Category and Product to identify major contributors.
•	Donut chart —Total Order count sales by Payment Method.
•	Line and Clustered Column chart — Sales and quantity by Category, with Region or Payment Method as the legend.
•	Slicers — Region, Category and Stock Details.





 




10. Findings and Insights
•	Total recorded sales were 6,164,336.32 across 1,000 distinct orders, with 25,581 units recorded.
•	North was the highest-sales region at 1,737,386.19 (28.2% of sales); South was the lowest at 1,299,189.92.
•	Electronics was the leading category at 4,192,529.43 (68.0% of sales).
•	Laptop was the highest-sales product at 2,131,323.25.
•	Credit Card had the highest sales total among payment methods at 1,456,677.24.
•	Store-12 was the top store by recorded sales at 443,379.29.
•	The supplied stock labels show 395 records marked High Stock,411 records marked Medium Stock and 194 marked Low Stock. These labels should be validated against inventory quantities/reorder thresholds before making replenishment decisions.
•	Average recorded discount was 6.67%. Average sales per order were 6,164.34.

11. Conclusion
The Excel and Power BI mini project turns 1,000 retail transaction records into a structured sales-performance report. The dataset records 6,164,336.32 in sales and 25,581 units across the reporting period. Electronics leads category sales, North leads regional sales, and Laptop is the leading product by recorded sales. Excel supports data preparation and summary analysis, while Power BI can present the results through interactive KPIs, trends, comparisons, and slicers. The report should be refreshed and validated if the underlying dataset or business definitions change.
