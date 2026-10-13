Restaurant Orders Analysis Dashboard | Power BI

Project Overview

This project focuses on analyzing restaurant order data using Microsoft Power BI. The objective is to clean and prepare data, create relationships, calculate KPIs using DAX, build visualizations, and develop an interactive dashboard to generate business insights and recommendations.

Tools Used

- Microsoft Power BI Desktop
- Power Query Editor
- DAX (Data Analysis Expressions)
- CSV Dataset

Dataset

The project uses two tables:

1. Order Details: Contains order IDs, item IDs, and order date and time information.
2. Menu Items: Contains menu item IDs, item names, categories, and prices.

Task 1: Data Import

- Imported two restaurant datasets into Power BI.
- Loaded the "order_details" and "menu_items" tables.
- Reviewed the available columns and data types.

Task 2: Data Cleaning and Preparation

- Reordered the "order_id" column to the second position.
- Merged the order date and order time columns.
- Renamed the merged column to "Order date & time".
- Prepared the data for analysis using Power Query.

Task 3: Data Modeling

- Connected "menu_items[menu_item_id]" with "order_details[item_id]".
- Created a one-to-many (1:*) relationship.
- Used the relationship to analyze order details by menu item, category, and price.

Task 4: DAX Measures and KPIs

Created four KPI measures:

- Total Sales
- Total Orders
- Average Order Value
- Total Records

These KPIs help summarize restaurant sales and order performance.

Task 5: Data Visualization

Created the following visualizations:

- KPI Cards
- Monthly Sales Trend
- Top 5 Selling Products
- Orders by Category
- Item Details Table

Task 6: Interactive Dashboard

Developed an interactive Restaurant Orders Dashboard containing:

- Four KPI cards
- Two slicers for filtering data
- Monthly Sales Trend chart
- Top 5 Sales-Performing Products chart
- Orders by Category chart
- Item Details table

The dashboard uses appropriate visualizations, titles, spacing, and layout to make the information easy to understand.

Task 7: Business Insights and Recommendations

Key Insights

- Reviewed total revenue and total orders.
- Identified March as the highest-sales month.
- Analyzed the top five selling products.
- Compared order performance across categories.
- Examined monthly sales trends and item-level details.

Recommendations

- Promote top-selling products to maintain sales performance.
- Review lower-performing categories and consider suitable promotions.
- Plan inventory according to monthly sales trends.
- Monitor KPIs regularly to track business performance and support better decisions.

Project Folder Structure

Assignment-5/
├── Dataset/
│   ├── order_details.csv
│   └── menu_items.csv
├── Logo
├── Dashboard.pbix
└── README.md

Conclusion

This project demonstrates practical Power BI skills, including data import, data cleaning, data modeling, DAX calculations, data visualization, interactive dashboard development, and business analysis.

The dashboard helps transform restaurant order data into meaningful information for understanding sales trends and supporting business decisions.