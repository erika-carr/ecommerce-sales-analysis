# E-Commerce Sales Performance Dashboard

## Project Overview

This project analyzes online retail sales data to identify revenue trends, top-performing products, and geographic performance. The dashboard provides actionable insights into sales patterns, customer behavior, and business performance across different products and regions.

## Business Questions Answered

- **What are the overall revenue trends over time?**
- **Which products generate the most revenue?**
- **Which geographic regions drive the most sales?**
- **How does revenue vary by month and season?**
- **What is the average transaction value?**

## Data Source

- **Dataset:** Online Retail II UCI Dataset
- **Source:** Kaggle
- **Size:** 1,048,576 transactions
- **Time Period:** [Insert date range from your data - e.g., Jan 2009 - Dec 2011]
- **Geography:** Multi-country e-commerce data

## Data Columns

| Column | Description |
|--------|-------------|
| Invoice | Unique transaction identifier |
| StockCode | Product code |
| Description | Product name |
| Quantity | Units sold per transaction |
| InvoiceDate | Date and time of transaction |
| Price | Unit price of product |
| Customer ID | Unique customer identifier |
| Country | Customer location |
| Revenue (Calculated) | Quantity × Price |
| Month (Calculated) | Month-Year extracted from InvoiceDate |

## Tools & Technologies Used

- **Data Preparation:** Microsoft Excel
- **Visualization:** Tableau Public
- **Data Format:** CSV
- **Formulas Used:** Revenue calculation (Quantity × Price), Month extraction

## Dashboard Contents

### 📊 Dashboard Overview

**Visualization 1: Revenue Trends Over Time**
- Shows total revenue by month across the entire dataset
- Identifies seasonal patterns and growth trends
- Helps understand peak sales periods

**Visualization 2: Top 10 Products by Revenue**
- Bar chart ranking products by total revenue generated
- Includes exact revenue figures for each product
- Reveals which products are the biggest revenue drivers

**Visualization 3: Top 10 Countries by Revenue**
- Geographic analysis of sales performance
- Shows which markets contribute most to overall revenue
- Useful for regional strategy and market focus

## Key Findings

[Add 2-3 findings from your dashboard, such as:]
- Example: "Revenue peaked in [Month/Season] with $X in sales"
- Example: "The top product generated $X in revenue, accounting for X% of total sales"
- Example: "[Country] is the strongest market with $X in revenue, followed by [Country]"
- Example: "Monthly revenue ranges from $X to $X, with an average of $X"

## Data Preparation Process

- Removed transactions with missing prices or descriptions to ensure data quality
- Created Revenue column by multiplying Quantity × Price for each transaction
- Extracted Month-Year from InvoiceDate for time-series analysis
- Handled approximately 1 million transactions, filtering out invalid entries

## How to Use This Dashboard

1. **View the Dashboard:** Open `ecommerce_sales_dashboard.png` to see the static visualization
2. **Interactive Version:** Download `Ecommerce_Sales_Dashboard.twbx` and open in Tableau Public or Tableau Desktop
3. **Explore Trends:** Hover over charts to see exact values
4. **Identify Patterns:** Look for seasonal trends, top performers, and geographic insights
5. **Export Data:** Right-click on visualizations to export underlying data

## Skills Demonstrated

✅ Data cleaning and handling of large datasets (1M+ rows)  
✅ Creating calculated fields (Revenue, Month extraction)  
✅ Advanced Tableau visualizations (time-series, rankings, comparisons)  
✅ Business intelligence and KPI tracking  
✅ Identifying patterns in multi-dimensional data  
✅ Communicating insights through visual analytics  

## Files Included

```
ecommerce-sales-project/
├── README.md                                    # This file
├── ecommerce_sales.csv                          # Dataset with calculated columns
├── Ecommerce_Sales_Dashboard.twbx               # Tableau workbook (interactive)
└── ecommerce_sales_dashboard.png                # Dashboard screenshot
```

## How to Reproduce

1. Download `ecommerce_sales.csv`
2. Open Tableau Public
3. Connect to the CSV file
4. Create three sheets:
   - Revenue over time (line/bar chart by Month)
   - Top 10 products by revenue (bar chart)
   - Top 10 countries by revenue (bar chart)
5. Combine into a single dashboard
6. Add title, format, and style as desired
7. Add data labels to bar charts for clarity

## Insights & Recommendations

Based on the dashboard analysis:
- Focus inventory and marketing efforts on top-performing products
- Invest in regional expansion in high-performing countries
- Plan inventory and staffing around peak revenue seasons
- Investigate underperforming regions for growth opportunities

## Future Enhancements

- Add customer lifetime value (CLV) analysis
- Implement cohort analysis for customer retention trends
- Create region-specific dashboards with deeper drill-down capability
- Add profitability analysis (costs vs. revenue)
- Implement predictive forecasting for future revenue
- Add product category breakdowns
- Create customer segmentation analysis

## Technical Notes

- Dataset contains some transactions with missing prices or descriptions (filtered in visualizations)
- Revenue calculations handle decimal prices and quantities
- Month extraction uses TEXT function to standardize date format
- Dashboard filters allow exploration of specific time periods and regions

## Author

[Your Name]  
Data Analysis Portfolio Project  
March 2026

## Contact

[Your Email/LinkedIn]

---

*This project demonstrates practical skills in sales analytics, data visualization, and business intelligence—core competencies for entry-level data analyst roles.*