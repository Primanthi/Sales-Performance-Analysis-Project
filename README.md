# PIZZA SALES ANALYSIS

## Project Overview

This project focuses on analyzing Pizza Sales data using Power BI & SQL to generate actionable business insights related to overall business performance, customer ordering behavior and product sales trends.

The project was designed to analyze transactional sales data, uncover key business insights and present the findings through interactive dashboards for better decision-making.

## Project Objectives

- Analyze overall sales performance
- Identify top-performing pizza products
- Analyze sales by pizza category and size
- Identify peak sales periods
- Monitor key sales KPIs
- Identify underperforming products

## Project Dashboard Preview

### Home Page

![Pizza Sales Dashboard - Home Page](Screenshots/home.png)

### Best/Worst Sellers

![Pizza Sales Dashboard - Best/Worst Sellers](Screenshots/sellers.png)

## Problem Statement

### KPI Requirements

Analyze key indicators for pizza sales data to gain insights into business performance. Specifically, calculate the following metrics:

1. **Total Revenue:** The sum of the total price of all pizza orders.
2. **Average Order Value (AOV):** The average amount spent per order, calculated by dividing the total revenue by the total number of orders.
3. **Total Pizzas Sold:** The sum of the quantities of all pizzas sold.
4. **Total Orders:** The total number of orders placed.
5. **Average Pizzas Per Order:** The average number of pizzas sold per order, calculated by dividing the total number of pizzas sold by the total number of orders.

### Charts Requirements

Visualize various aspects of the pizza sales data to gain insights and understand key trends. The following requirements were identified for creating charts:

1. **Daily Trend for Total Orders:** Create a bar chart that displays the daily trend of total orders over a specific time period. This chart will help identify patterns or fluctuations in order volumes on a daily basis.
2. **Monthly Trend for Total Orders:** Create a line chart that illustrates the hourly trend of total orders throughout the day. This chart will allow identification of peak hours or periods of high order activity.
3. **Percentage of Sales by Pizza Category:** Create a pie chart that shows the distribution of sales across different pizza categories. This provides insights into the popularity of various pizza categories and their contribution to overall sales.
4. **Percentage of Sales by Pizza Size:** Generate a pie chart that represents the percentage of sales attributed to different pizza sizes. This helps understand customer preferences for pizza sizes and their impact on sales.
5. **Total Pizzas Sold by Pizza Category:** Create a funnel chart that presents the total number of pizzas sold for each pizza category. This allows comparison of the sales performance of different pizza categories.
6. **Top 5 Best Sellers by Revenue, Total Quantity and Total Orders:** Create a bar chart highlighting the top 5 best-selling pizzas based on revenue, total quantity and total orders. This helps identify the most popular pizza options.
7. **Bottom 5 Worst Sellers by Revenue, Total Quantity and Total Orders:** Create a bar chart showcasing the bottom 5 worst-selling pizzas based on revenue, total quantity and total orders. This enables identification of underperforming or less popular pizza options.

## Data Description

| Field | Description |
|---|---|
| `pizza_id` | Primary Key; unique ID of pizza. |
| `order_id` | Unique ID of order. One order may contain multiple pizzas ordered. |
| `pizza_name_id` | A unique SKU name for Pizza type with description and size, separated by underscores (e.g., `bbq_ckn_l` is barbecue chicken pizza of large size). |
| `quantity` | Number of pizzas ordered. Range of values is usually 1 to 7 or 8. |
| `order_date` | Date of order. Format: DD-MM-YYYY. |
| `order_time` | Time of order. Format: HH:MM:SS. |
| `unit_price` | Price of an individual pizza in dollars. Numerical, float value up to 2 decimal places. |
| `total_price` | Total price of pizza in dollars. Numerical, float value up to 2 decimal places. |
| `pizza_size` | Size of pizza among S, M and L. |
| `pizza_category` | Category of pizza among Classic, Supreme, Veggie and Chicken. |
| `pizza_ingredients` | Comma-separated list of ingredients of the pizza. |
| `pizza_name` | Name of the pizza (consumer-readable). |

## Tools & Technologies

1. MS Office / Excel
2. MS SQL Server
3. SQL Server Management Studio (SSMS)
4. Power BI

## Key Insights from the Dashboard

- Large pizzas represented the highest proportion of total sales, indicating a strong customer preference for larger pizza sizes.
- Friday and Saturday recorded the highest order volumes, highlighting increased customer demand toward the weekend.
- July and January showed the highest order activity during the analyzed period.
- Thai Chicken Pizza generated the highest revenue among the pizza products.
- Classic Deluxe Pizza recorded the highest number of orders.
- Brie Carre Pizza was one of the lowest-performing products based on revenue and order volume.

## Business Recommendations

- **Focus on high-performing products:** Maintain sufficient inventory and promote top-performing pizzas to capitalize on strong customer demand.
- **Optimize weekend operations:** Since order volumes are higher toward the weekend, increase staff availability and prepare sufficient ingredients during these periods to handle higher demand efficiently.
- **Promote underperforming pizzas:** Consider targeted discounts, combo offers, or promotional campaigns for low-performing pizzas to increase their sales and evaluate whether they should remain on the menu.
- **Leverage popular pizza sizes:** Since larger pizza sizes account for a significant proportion of sales, consider creating attractive meal deals or bundle offers around these sizes to encourage higher-value orders.
- **Use seasonal sales patterns:** Analyze periods with higher order volumes and plan inventory, staffing, and marketing campaigns accordingly to take advantage of increased demand.
- **Review the product mix regularly:** Monitor revenue, quantity sold, and order frequency by pizza to identify changing customer preferences and make informed menu and pricing decisions.

## Conclusion

This project provided a comprehensive analysis of pizza sales performance using SQL and Power BI. By transforming raw transactional data into meaningful visualizations and key performance indicators, the analysis identified important sales patterns, customer preferences, and product performance.

The dashboard highlighted differences in sales across pizza sizes, categories, products, and time periods, providing a clear view of overall business performance. These insights can help the business improve inventory planning, optimize promotional activities, focus on high-performing products, and address underperforming products.

Overall, the project demonstrates how data analysis and interactive dashboards can transform raw sales data into actionable business insights and support data-driven decision-making.
