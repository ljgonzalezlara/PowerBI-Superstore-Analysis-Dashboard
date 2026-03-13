# Sales Performance & Profitability Analysis Report

## Table of Contents
- [Objective](#objective)
- [Dataset](#dataset)
- [Tools](#tools)
- [Methods](#methods)
- [Overview](#overview)
- [Interactive Dashboard Demo](#interactive-dashboard-demo)
- [Insights](#insights)
- [Recommendations](#strategic-recommendations)

## Objective
Analyze the Superstore dataset to build an interactive Power BI dashboard that converts transactional data into actionable business insights.

The analysis explores revenue trends, profit margins, customer value, and product performance across regions, categories, and time periods. It also evaluates the impact of discounting on profitability and identifies key drivers of financial performance to support data-driven business decisions.

## Dataset
- [Superstore Dataset](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)
- [Fields](#fields)

## Tools
- Power BI (Power Query, Power Pivot, DAX)

## Methods
- Data Cleaning and Preprocessing
- Data Modeling
- DAX measures
- Data Analysis with Visuals

---

## Overview
The report consists of four interactive pages with dynamic slicers for filtering by year, quarter, and region, along with drill-through functionality and time intelligence. These features enable both high-level monitoring and detailed segment exploration.

Dashboard Pages:
- **Executive Summary:** High-level view of total sales, profit, and key performance indicators across regions and time.
- **Product Profitability:** Analysis of category and sub-category performance to identify top- and under-performing products.
- **Segment & Region Profitability:** Exploration of customer segments, customer profitability, and regional performance.
- **Customer Profit Leakage:** Investigation of drivers behind low-profit customers, including CLV analysis, the impact of discounting, and correlations between customer lifespan and total profit.

---
## Interactive Dashboard Demo
Public sharing of this Power BI dashboard is restricted. The short video linked below demonstrates the dashboard’s interactive features, including slicers, filters, drill-through, and drill-down functionality.

- [Superstore Analysis Report](https://youtu.be/vOsRzdfNOKc)


## Insights

### Executive Summary

![](https://github.com/ljgonzalezlara/PowerBI-Superstore-Analysis-Dashboard/blob/1d3257646f05e07a7b400fef3e9696aaee872dd2/Images/Page%201.png)

**Key Insights**
- Profit grew 88.7% from 2014 to 2017, increasing from $49.5K to $93.4K, indicating strong overall growth.
- Demand consistently peaks in Q4, suggesting strong seasonality in purchasing behavior.
- The West region generates the highest profit margins, outperforming other regions.
- Technology products produce the highest overall profit, making it the most valuable product category.

Note: The dataset is a sample dataset. Some patterns, such as seasonality, may be weaker than typically observed in real-world data.

### Product Profitability

![](https://github.com/ljgonzalezlara/PowerBI-Superstore-Analysis-Dashboard/blob/1d3257646f05e07a7b400fef3e9696aaee872dd2/Images/Page%202.png)
![](https://github.com/ljgonzalezlara/PowerBI-Superstore-Analysis-Dashboard/blob/1d3257646f05e07a7b400fef3e9696aaee872dd2/Images/Page%203.png)

**Key Insights**
- Several subcategories consistently generate losses, particularly Tables, Bookcases, and Supplies.
- High discounting (23–35%) is common in Tables, Binders, and Machines, which frequently results in reduced or negative profit margins.
- Phones, Copiers, Paper, and Binders generate the strongest profits, making them key revenue drivers.

### Segment & Region Profitability

![](https://github.com/ljgonzalezlara/PowerBI-Superstore-Analysis-Dashboard/blob/1d3257646f05e07a7b400fef3e9696aaee872dd2/Images/Page%204.png)

**Key Insights**
- The Consumer segment generates the highest overall profit across all regions.
- The Central region applies the highest average discounts, which may contribute to weaker margins.
- The West region maintains the lowest average discounts, which likely contributes to its stronger profitability.

### Customer Profit Leakage

![](https://github.com/ljgonzalezlara/PowerBI-Superstore-Analysis-Dashboard/blob/1d3257646f05e07a7b400fef3e9696aaee872dd2/Images/Page%205.png)

**Key Insights**
- Customer Lifetime Value (CLV) shows little correlation with profitability, largely due to aggressive discounting.
- Customer lifespan has only a weak relationship with profit generation.
- Several longstanding customers generate negative profit, suggesting that discounting policies may outweigh long-term value.
- Many customers purchase across multiple regions, indicating geographically distributed purchasing patterns.

---

## Strategic Recommendations
- Reevaluate discounting strategies in underperforming subcategories such as Tables, Binders, and Machines to improve margins.
- Discontinue or reassess the Supplies subcategory, which consistently generates losses.
- Increase focus on high-performing products, particularly Phones, Copiers, and Paper.
- Optimize inventory and marketing strategies for Q4, when demand consistently peaks.
- Adjust loyalty or discount programs for long-term customers to ensure they contribute positively to profitability.

---

## Fields
- Row ID => Unique ID for each row.
- Order ID => Unique Order ID for each Customer.
- Order Date => Order Date of the product.
- Ship Date => Shipping Date of the Product.
- Ship Mode => Shipping Mode specified by the Customer.
- Customer ID => Unique ID to identify each Customer.
- Customer Name => Name of the Customer.
- Segment => The segment where the Customer belongs.
- Country => Country of residence of the Customer.
- City => City of residence of of the Customer.
- State => State of residence of the Customer.
- Postal Code => Postal Code of every Customer.
- Region => Region where the Customer belong.
- Product ID => Unique ID of the Product.
- Category => Category of the product ordered.
- Sub-Category => Sub-Category of the product ordered.
- Product Name => Name of the Product.
- Sales => Sales of the Product.
- Quantity => Quantity of the Product.
- Discount => Discount provided.
- Profit => Profit/Loss incurred.

Disclaimer:
This project was created for educational and practice purposes only. The analysis and results presented are based on simulated or publicly available data and should not be used to inform real-world business decisions without further validation.
