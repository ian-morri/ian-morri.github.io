---
layout: post
title: E-Commerce Sales Analytics
image: "_posts/e_commerce.jpg"
tags: [Business Analytics, SQL, Python, Tableau, Machine Learning]
---

# E-Commerce Sales Analytics & Forecasting
## Business Analytics Capstone Project
### Turning 527K+ Transactions into Strategic Insights
#### Using SQL, Python, Tableau & Machine Learning
##### Focused on Revenue Optimization & Inventory Efficiency

---

## Project Overview

This project analyzes over **527,000 e-commerce transactions** from a UK-based online retailer to identify:

* Revenue drivers  
* Seasonal demand trends  
* Customer segmentation opportunities  
* Inventory inefficiencies  
* International expansion potential  

The objective was to transform raw transactional data into **actionable business recommendations**.

---

## The Business Problem

The company lacked clear visibility into:

* Seasonal revenue concentration
* Bulk vs. individual purchasing behavior
* Low-performing product impact
* Geographic sales distribution
* Inventory optimization opportunities

The goal was to support data-driven decision-making using structured analytics.

---

## Dataset Overview

* 527,764 transactions  
* 13 months of sales data  
* 38 countries  
* 3,768 unique products  

Key variables included:

1. Transaction ID  
2. Date  
3. Product ID & Name  
4. Price (£)  
5. Quantity  
6. Customer ID  
7. Country  

---

## Tools & Technologies Used

* SQL  
    * Data cleaning  
    * Aggregation  
    * Customer segmentation  
* Python  
    * Correlation analysis  
    * Automation scripts  
    * Trend analysis  
* Tableau / Power BI  
    * Interactive dashboards  
    * Sales visualization  
* Weka  
    * OneR  
    * ZeroR  
    * J48 Decision Tree  
* Excel / R  
    * Descriptive statistics  

---

## Key Insights

### Revenue is Highly Seasonal

Sales peaked in **November** with a noticeable decline in December.

This indicates strong Q4 dependency and highlights the importance of:

* Early inventory planning  
* Pre-holiday marketing campaigns  
* Forecast-driven stocking strategies  

---

### Clear B2B vs B2C Segmentation

Approximately 35% of customers were high-volume buyers.

High standard deviation in quantity confirmed a dual purchasing pattern:

* Bulk B2B buyers  
* Individual B2C consumers  

Strategic recommendation:

1. Dedicated bulk pricing tiers  
2. Separate marketing strategies  
3. Incentive-based loyalty programs  

---

### Inventory Inefficiency Identified

156 products sold only once during the 13-month period.

This suggests capital and warehouse space tied up in low-performing SKUs.

Recommended actions:

* Discontinue consistently underperforming products  
* Reallocate capital toward high-demand items  
* Improve SKU performance tracking  

---

## Example SQL Aggregation

Below is a simplified example of how revenue was analyzed:

SELECT
Country,
SUM(Price * Quantity) AS Total_Revenue
FROM sales_data
GROUP BY Country
ORDER BY Total_Revenue DESC;

---

## 📊 Dashboard Visualizations

Dashboards included:

* Monthly sales trends  
* Cancellation patterns  
* Top 10 countries by revenue  
* Top-selling products by quantity  
* Daily average sales trends  

These dashboards support executive-level decision-making and operational monitoring.

---

## Final Recommendations

1. Launch marketing campaigns before Q4 peak.  
2. Implement bulk pricing incentives for B2B buyers.  
3. Remove persistently low-performing SKUs.  
4. Deploy predictive forecasting models.  
5. Automate executive dashboards.  
6. Integrate web analytics for customer behavior insights.  

---

## Limitations

* Only 13 months of data  
* No customer feedback or sentiment data  
* No multi-year seasonal validation  

Future improvements should include 3–5 years of historical data for stronger forecasting accuracy.

---

## Skills Demonstrated

* Data Cleaning & Transformation  
* SQL Querying & Aggregation  
* Time-Series Analysis  
* Business Intelligence Dashboarding  
* Statistical Analysis  
* Machine Learning Classification  
* Inventory Optimization Strategy  
* Business-Focused Recommendation Development  

---
