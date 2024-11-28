
![chart](https://github.com/user-attachments/assets/4c6e959a-8a56-4f8c-abf5-d92d25a68f3a)


# Order Frequency Dashboard


## Problem Statement

Online retailers struggle to analyze order frequency and sales data across various products, categories, and countries.


## Insights

This dashboard provides actionable insights into:


- Monthly order frequency by product
- Total sales by product and category
- Product category distribution
- Country-wise order distribution
- Monthly sales trends


## Data Description


| Field Name | Data Type | Description |
| --- | --- | --- |
| Order ID | Number | Unique order identifier |
| Product | String | Name of the product ordered |
| Category | String | Product category (e.g., Electronics, Fashion) |
| Amount | Currency | Total sales amount for the order (e.g., $100.00) |
| Date | Date | Date the order was placed (YYYY-MM-DD) |
| Country | String | Country where the order was placed (e.g., USA, Canada) |


## Dashboard Components


## One-Dimensional Pivot Table

- Line Chart: Monthly Orders by Product
    - Highest: Banana (71 orders)
- Bar Chart: Total Sales by Product
    - Highest: Banana ($340,295)
- Pie Chart: Product Categories
    - Highest: Fruit (67%)
- Column Chart: Country Orders
    - Highest: [Country Name] (57 orders)
- Area Chart: Monthly Sales
    - Highest: May ($303,339)


## Two-Dimensional Pivot Table

- Column Chart: Orders by Category
    - Banana (Fruits): $340,295
    - Cabbage (Vegetables): $142,439
- Column Chart: Category Order Frequency
    - Banana (Fruits): Highest frequency
    - Cabbage (Vegetables): Highest frequency
- Area Chart: Monthly Orders by Category
    - May: Fruits (29), Vegetables (11)
- Bar Chart: Average Order Value
    - Cabbage: $5,276
    - Mango: $5,189
- Line Chart: Country Orders by Category
    - Fruits: United States (42)
    - Vegetables: Germany (20)


## Features

- Interactive pivot tables for dynamic data analysis
- Visualizations for monthly orders, total sales, product categories, country orders, and monthly sales
- Slicers for filtering data by product, category, and country
- Hyperlinks to related data sources or additional information


Compatibility

- Excel version: 2013+

