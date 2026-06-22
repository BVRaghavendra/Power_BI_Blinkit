# Blinkit Data Analysis Dashboard

A Power BI dashboard analyzing Blinkit's sales performance, customer satisfaction, and inventory distribution across outlets, helping identify growth opportunities and operational insights.

## Project Overview

This project presents a comprehensive Power BI dashboard built on Blinkit's grocery sales data. It visualizes key business metrics across outlet types, locations, and product categories to surface actionable insights for sales optimization, inventory planning, and customer experience improvement.

## Dataset

The dashboard is built on the `BlinkIT_Grocery_Data.xlsx` dataset, which contains 8,523 records with the following fields:

| Column | Description |
|---|---|
| Item Identifier | Unique ID for each item |
| Item Fat Content | Low Fat or Regular |
| Item Type | Product category (e.g., Fruits and Vegetables, Snack Foods, Health and Hygiene) |
| Item Weight | Weight of the item |
| Item Visibility | Percentage of total display area allocated to the item in a store |
| Outlet Identifier | Unique ID for each outlet |
| Outlet Establishment Year | Year the outlet was established |
| Outlet Size | Small, Medium, or High |
| Outlet Location Type | Tier 1, Tier 2, or Tier 3 |
| Outlet Type | Grocery Store, Supermarket Type1, Type2, or Type3 |
| Sales | Revenue generated from the item |
| Rating | Customer rating for the item |

## Key Performance Indicators

The dashboard tracks the following primary KPIs:

- **Total Sales**: Overall revenue generated from all items sold ($1.20M)
- **Average Sales**: Average revenue per sale ($141)
- **Number of Items**: Total count of different items sold (8,523)
- **Average Rating**: Average customer rating for items sold (3.9 out of 5)

## Features

- **Filter Panel**: Filter data by outlet location type, outlet size, and item type
- **Outlet Establishment Trend**: Visualizes the growth of outlet establishments from 2012 to 2022
- **Fat Content Analysis**: Breaks down sales by low fat and regular fat products
- **Item Type Distribution**: Shows sales distribution across various product categories
- **Outlet Size and Location Analysis**: Insights on sales performance by outlet size and location tier
- **Outlet Type Comparison**: Compares outlet types based on sales, number of items, average sales, ratings, and item visibility

## Insights and Conclusions

- Strong overall sales performance with over $1M in total sales
- Consumer preference for low-fat products, indicating health-conscious buying habits
- Fruits, vegetables, and snack foods are the top-selling categories
- Medium-sized outlets in Tier 3 locations show the highest profitability
- Supermarkets generate higher sales volumes, while grocery stores have better item visibility

## Tools Used

- **Power BI**: Dashboard design and visualization
- **Excel**: Source data storage (BlinkIT_Grocery_Data.xlsx)

## Repository Contents

| File | Description |
|---|---|
| `BlinkIT Grocery Data.xlsx` | Source dataset used for the dashboard |
| `Blinkit-Dashboard.docx` | Project documentation and dashboard summary |
| `Blinkit-Dashboard.png` | Screenshot of the Power BI dashboard |
| `BlinkitDashboard.pbix` | Power BI project file |
| `Dashboard_PowerBI_Blinkit.png` | Screenshot of the Power BI dashboard |
| `README.md` | Project overview and documentation |

## How to Use

1. Clone this repository
2. Open `BlinkitDashboard.pbix` in Power BI Desktop, or review `BlinkIT Grocery Data.xlsx` to explore the underlying data
3. Use the filter panel within the dashboard to explore sales performance by outlet location, size, and item type

## Note

This analysis was conducted as part of a project and is for educational purposes only.
