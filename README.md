# AtliQ Hardwares Sales Report

This repository contains the sales report for AtliQ Hardwares, covering various product performance metrics and sales data from 2020 to 2021. The report is designed and created using Power BI, leveraging advanced data modeling, DAX calculations, and business intelligence best practices.

## Report Overview

The report is divided into several sections:
- **Top 10 Products:** A list of the top-selling products in 2020 and 2021, with a comparison of sales growth.
- **Division Level Report:** A breakdown of sales by division, showing the growth from 2020 to 2021.
- **Top and Bottom Products by Quantity:** A summary of the top and bottom 5 products based on quantity sold.
- **New Products - 2021:** Sales data for new products introduced in 2021.
- **Top 5 Countries - 2021:** The countries with the highest sales in 2021.

## Report Creation Details

### Power BI Features Used:
- **Data Import and Transformation:** The data was imported from various sources (e.g., Excel, SQL databases) and transformed using Power Query for cleaning and preparation.
- **Data Modeling:** Relationships were established between tables (Product, Sales, Customer, Region) to create a robust data model.
- **DAX Calculations:** Advanced DAX functions were used to create calculated columns and measures, such as total sales, growth percentages, and ranking products.
  - **Example DAX Measure:** 
    ```DAX
    Total Sales = SUM(Sales[Amount])
    ```
  - **Growth Percentage Calculation:**
    ```DAX
    Growth % = DIVIDE([Total Sales 2021] - [Total Sales 2020], [Total Sales 2020], 0)
    ```
- **Visualizations:**
  - **Tables and Matrices:** Used to display data like the Top 10 Products, Division Level Sales, and New Products.
  - **Conditional Formatting:** Applied to highlight key trends and data points.
  - **Map Visualization:** Used for geographical representation of sales by country.

### Business Terminology:
- **KPIs (Key Performance Indicators):**
  - **Gross Sales:** Total revenue generated before deductions.
  - **Net Sales:** Revenue after returns, discounts, and allowances.
  - **YoY Growth:** Year-over-year growth percentage.
  - **Market Share:** Percentage of sales captured by a product in its market.

- **Filtering and Drill-Downs:**
  - Filters and slicers were added to allow users to explore data by product, region, and division.
  - Drill-down capabilities enable deeper insights from division-level down to specific product performance.

## Preview

![AtliQ Hardwares Report Preview](path-to-your-image/preview.png)

### Top 10 Products (2021 vs 2020)
| Product          | 2020 Sales (USD) | 2021 Sales (USD) | Growth (%) |
|------------------|------------------|------------------|------------|
| AQ Electron 4    | 3.0M             | 19.4M            | 541.3%     |
| AQ GT 21         | 0.8M             | 4.4M             | 461.1%     |
| AQ Home Allin1   | 0.7M             | 5.2M             | 669.0%     |
| AQ LION x1       | 0.0M             | 0.8M             | 1619.5%    |
| AQ LION x2       | 0.1M             | 0.9M             | 1668.9%    |
| AQ LION x3       | 0.1M             | 1.2M             | 1692.3%    |
| AQ Mx NB         | 0.0M             | 1.4M             | 5623.5%    |
| AQ Pen Drive DRC | 0.6M             | 3.8M             | 487.7%     |
| AQ Smash 2       | 0.4M             | 11.2M            | 2489.5%    |
| AQ Zion Saga     | 0.7M             | 3.6M             | 428.5%     |

### Division Level Report (2021 vs 2020)
| Division | 2020 Sales (USD) | 2021 Sales (USD) | Growth (%) |
|----------|------------------|------------------|------------|
| N & S    | 51.4M            | 94.7M            | 84.4%      |
| P & A    | 105.2M           | 338.4M           | 221.5%     |
| PC       | 40.1M            | 165.8M           | 313.7%     |

### Top and Bottom Products by Quantity (2021)
- **Top 5 Products:**
  - AQ Gamers: 3.4M units
  - AQ Gamers Ms: 4.0M units
  - AQ Master wired x1 Ms: 4.2M units
  - AQ Master wireless x1: 3.4M units
  - AQ Master wireless x1 Ms: 4.1M units

- **Bottom 5 Products:**
  - AQ Gamer 1: 51.7K units
  - AQ GEN Z: 63.1K units
  - AQ Home Allin1: 15.2K units
  - AQ HOME Allin1 Gen 2: 8.9K units
  - AQ Smash 2: 36.0K units

### New Products - 2021
| Product              | 2020 Sales (USD) | 2021 Sales (USD) |
|----------------------|------------------|------------------|
| AQ Clx3              | -                | 4.4M             |
| AQ Electron 3 3600   | -                | 14.2M            |
| AQ Gen Y             | -                | 19.5M            |
| AQ GEN Z             | -                | 11.7M            |
| AQ HOME Allin1 Gen 2 | -                | 3.5M             |
| AQ Lumina Ms         | -                | 4.2M             |
| AQ Marquee P3        | -                | 4.9M             |
| AQ Marquee P4        | -                | 1.7M             |
| AQ Maxima Ms         | -                | 13.7M            |
| AQ MB Lito           | -                | 2.8M             |
| AQ MB Lito 2         | -                | 2.3M             |
| AQ Qwerty            | -                | 22.0M            |
| AQ Qwerty Ms         | -                | 15.4M            |
| AQ Trigger           | -                | 20.7M            |
| AQ Trigger Ms        | -                | 17.9M            |
| AQ Wi Power Dx3      | -                | 17.2M            |

### Top 5 Countries - 2021
| Country       | 2021 Sales (USD) |
|---------------|------------------|
| Canada        | 35.1M            |
| India         | 161.3M           |
| South Korea   | 49.0M            |
| United Kingdom| 34.2M            |
| USA           | 87.8M            |


