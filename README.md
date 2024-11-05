# E-commerce Sales Analysis Dashboard

## Project Overview
This Power BI dashboard analyzes e-commerce sales data, providing insights into total revenue, profit, quantity sold, and average order value (AOV). It offers segmented views by city, customer, product category, and payment method, aiding quick, data-driven decisions.

## Data Source
- **Orders Dataset**: General order information, including order ID, dates, customer name, city and state.
- **Details Dataset**: Item-level details like product category, quantity, profit, average order value, sub-category, payment mode, amount and price.

The datasets are connected via `Order ID` for a relational model.

## Key Metrics & Visualizations
- **Summary Cards**: Total Amount, Profit, Quantity, and AOV.
- **Visuals**:
  - Profit by City, Profit by Month, and Profit by Sub-Category.
  - Quantity by Category and by Payment Mode.
  - Profit by Customer.

### Filters
Quarter and yearly filters allow period-specific analysis.

## Requirements
- Power BI Desktop
- Orders and Details data linked by `Order ID`

## How to Use
1. Open the dashboard in Power BI.
2. Use filters to view specific periods.
3. Hover and click on visuals to explore data details interactively.
