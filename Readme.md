# Flower Co Analytics Dashboard
![image](https://github.com/user-attachments/assets/a7700bce-242c-4bcb-a186-4beebe9b7ca9)
# Plant Co. Quantity Performance Dashboard 2023

This Power BI dashboard presents a detailed view of Plant Co.'s quantity performance across various dimensions for the year 2023. It enables business stakeholders to analyze current year trends, compare performance with previous years, and identify country, month, and product-specific patterns.

## Overview

The dashboard compares Year-To-Date (YTD) and Previous Year-To-Date (PYTD) quantities, offering visibility into growth patterns and performance gaps. It includes interactive visuals for deeper exploration by country, month, product type, and account.

### Key Metrics

- **PYTD**: 538.61K
- **YTD**: 555.66K
- **YTD vs PYTD**: 17.05K (Positive Growth)
- **Gross Profit % (GP%)**: 39.62%

These KPIs provide a snapshot of operational success and profitability.

## Visual Breakdown

### 1. YTD vs PYTD by Country

A tree map highlights each country's performance in terms of quantity change compared to the previous year. Negative values indicate underperformance (e.g., China: -9.76K, France: -9.36K), aiding in identifying countries needing attention.

### 2. YTD vs PYTD by Month

A waterfall chart visualizes monthly changes between YTD and PYTD, with green indicating increases and red indicating decreases. This makes seasonal trends and performance swings easy to interpret.

### 3. S_YTD and S_PYTD by Month and Product Type

A stacked column chart compares current and previous year quantities across different product types:
- Indoor
- Landscape
- Outdoor

This helps assess product category contributions over time.

### 4. S_YTD and GP% by Account

A scatter plot shows the distribution of accounts based on their current year quantity (S_YTD) and gross profit percentage (GP%). This identifies high-volume and high-margin accounts, guiding account management strategies.

## Filters and Interactivity

- The user can select **Quantity**, **Sales**, or **Gross Profit** as the main metric.
- A **YTD** year slicer allows analysis for a specific calendar year.
- Dynamic tooltips, highlighting, and slicers enable interactive and drill-down exploration.

## Use Cases

- Identify markets or countries underperforming compared to last year.
- Monitor product category trends across months.
- Understand the relationship between account size and profitability.
- Support strategic decisions on resource allocation, inventory, and sales efforts.

## Tools and Technologies

- Power BI Desktop
- DAX calculations for YTD/PYTD logic
- Custom visuals for tree maps, waterfall charts, and scatter plots
- Field parameters for switching between metrics

## How to Use

1. Load the `.pbix` file in Power BI Desktop.
2. Use slicers to select desired year or metric.
3. Hover over visuals to see precise quantity and GP% values.
4. Filter by product type or account size for detailed insights.

## Conclusion

This dashboard serves as a robust analytical tool for evaluating quantity performance, identifying business gaps, and tracking product trends. It helps Plant Co. make strategic decisions with data-driven insights.



