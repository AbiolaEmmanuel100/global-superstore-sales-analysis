# Global Superstore Sales & Profitability Analysis

## Business Objective
The objective of this project was to analyze sales performance and profitability across product categories and regions using the Global Superstore dataset. The analysis focused on identifying underperforming business areas, uncovering factors affecting profit margins, and providing data-driven recommendations to improve overall profitability.

---

## Dataset Overview
The project was conducted using the **Global Superstore** dataset, which contains transactional sales records including:

- Orders
- Products
- Customers
- Regions
- Sales Revenue
- Profit
- Discounts
- Shipping Information

---

## Data Preparation (SQL)

The dataset was cleaned and transformed using SQL before being imported into Power BI for visualization.

### Key Preparation Steps
- Selected relevant analytical columns
- Removed unnecessary fields
- Reviewed and handled missing values
- Validated total sales and profit aggregates
- Prepared a cleaned dataset for dashboard modeling

---

## Dashboard Development (Power BI)

An interactive two-page dashboard was developed to provide both executive-level insights and detailed profitability analysis.

### Dashboard Features
- Executive Overview Dashboard
- Profitability Deep Dive Dashboard
- KPI Cards for:
  - Total Sales
  - Total Profit
  - Profit Margin
- Interactive slicers for dynamic filtering
- Conditional formatting to highlight loss-making categories
- Scatter plot analysis for Discount vs Profit relationship
- Regional and sub-category performance analysis

---

# Executive Performance Overview

This dashboard provides a high-level summary of overall business performance, highlighting total sales, total profit, and profit margin across product categories and regions. Interactive slicers allow users to dynamically filter performance by time period and region.

### Key Insight
While overall sales performance is strong, profitability varies significantly across categories, indicating the need for deeper category-level investigation.

---

# Sales Trend Over Time

The sales trend visualization tracks revenue performance over time, helping identify seasonality patterns, growth trends, and fluctuations in demand.

### Key Insight
Revenue demonstrates consistent long-term growth with periodic fluctuations, suggesting seasonal demand cycles that can support forecasting and strategic planning.

---

# Profitability by Product Category

This visualization compares profit margin performance across major product categories to identify high-performing and underperforming business segments.

### Key Insight
- **Technology** generated the highest overall profitability.
- **Furniture** produced strong sales revenue but significantly weaker profit margins.

---

# Discount Impact on Profitability

A scatter plot was created to examine the relationship between average discount levels and total profit across product sub-categories.

### Key Insight
Sub-categories with higher average discount levels tend to generate lower or negative profit, indicating that aggressive discounting negatively impacts profitability.

---

# Sub-Category Profit Analysis

This detailed table analyzes sales, discount, and profit performance at the sub-category level. Conditional formatting was applied to highlight loss-making segments.

### Key Insight
The **Tables** sub-category recorded significant financial losses, primarily driven by excessive discounting, making it the largest contributor to weak Furniture profitability.

---

# Regional Profit Contribution

This analysis evaluates profitability across regions to identify geographic strengths and improvement opportunities.

### Key Insight
The **Central** region contributed the highest overall profit, while other regions showed opportunities for margin improvement through pricing optimization and product mix adjustments.

---

# Business Recommendations

Based on the analysis, the following recommendations were proposed:

- Review discount strategies for Furniture products
- Reduce excessive discounting on Tables
- Prioritize high-margin categories such as Technology
- Monitor regional pricing and profitability performance regularly
- Improve product mix optimization in underperforming regions

---

# Tools Used

- SQL
- Power BI
- Excel

---

# Project Conclusion

This project demonstrates end-to-end data analytics capability — from SQL-based data cleaning and preparation to interactive Power BI dashboard development and business insight generation.

The analysis successfully identified key profitability drivers, highlighted underperforming segments, and provided actionable business recommendations that support data-driven decision-making and revenue optimization.
