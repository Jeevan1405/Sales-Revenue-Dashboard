# Sales Revenue Dashboard

An interactive Power BI dashboard built to analyze e-commerce sales performance, uncover revenue and profit trends, and support data-driven business decisions across products, regions, and payment channels.

![Dashboard Preview](abstract-luxury-gradient-blue-background-smooth-dark-blue-with-black-vignette-studio-banner.jpg)

## Overview

This project transforms raw e-commerce order and transaction data into a single, decision-ready dashboard. It consolidates order details, profitability, and customer/location data to help stakeholders track sales performance, identify top-performing product categories, and evaluate regional and payment-mode trends at a glance.

## Objective

- Consolidate order and sales data from multiple sources into one unified data model
- Track key performance indicators: total sales, profit, order volume, and quantity sold
- Identify top-performing product categories, sub-categories, and states/cities
- Analyze payment mode distribution and its impact on sales
- Enable stakeholders to filter and drill down into sales trends for faster, more informed decisions

## Dataset

The dashboard is built on two linked datasets (joined on `Order ID`):

| File | Description | Key Fields |
|---|---|---|
| `Orders.csv` | Order-level and customer/location details | Order ID, Order Date, Customer Name, State, City |
| `Details.csv` | Transaction-level sales and profitability data | Order ID, Amount, Profit, Quantity, Category, Sub-Category, Payment Mode |

Combined, the dataset covers **500 orders** and **1,500 transaction line items** across categories including Electronics, Furniture, and Clothing.

## Key Features

- **KPI Summary Cards** — At-a-glance totals for Sales, Profit, Quantity, and Orders
- **Category & Sub-Category Breakdown** — Visual comparison of revenue and profit contribution by product category (Electronics, Furniture, Clothing) and sub-category (e.g., Chairs, Bookcases, Printers, Electronic Games)
- **Geographic Analysis** — Sales and profit distribution across Indian states and cities to highlight top-performing regions
- **Payment Mode Analysis** — Breakdown of order volume by payment method (COD, EMI, Credit Card, etc.)
- **Trend Visualization** — Time-based view of order and sales patterns across the dataset's date range
- **Interactive Filtering** — Slicers for category, region, and payment mode enabling dynamic, self-service exploration

## Tools & Technologies

- **Power BI Desktop** — Data modeling, DAX measures, and dashboard design
- **Power Query** — Data cleaning, transformation, and table relationships
- **CSV** — Source data format (Orders and Details)

## Project Files

```
Sales-Revenue-Dashboard/
├── Sales Revenue Dashboard.pbix   # Power BI report file
├── Orders.csv                     # Order & customer/location data
├── Details.csv                    # Transaction & profitability data
├── Sales Revenue Dashboard.pdf    # Exported dashboard preview
└── README.md
```

## How to Use

1. Clone or download this repository
2. Open `Sales Revenue Dashboard.pbix` in **Power BI Desktop**
3. If prompted, reconnect the data source paths to the local `Orders.csv` and `Details.csv` files
4. Use the slicers and visuals to explore sales, profit, and regional performance interactively

## Key Insights

- Product category and sub-category performance vary significantly in profit margin versus sales volume, highlighting where revenue is strong but profitability is thin (and vice versa)
- A small number of states/cities account for a disproportionate share of total orders, pointing to clear regional growth opportunities
- Payment mode preference (COD vs. EMI vs. Credit Card) varies by order value, offering a lens into customer purchasing behavior

## Author

**Jeevan H S**
[LinkedIn](https://linkedin.com/in/jeevan1405) | [GitHub](https://github.com/Jeevan1405)
