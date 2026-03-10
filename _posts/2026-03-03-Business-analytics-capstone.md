---
layout: post
title: E-Commerce Sales Analytics 
image: "/posts/ecommerce.jpg"
tags: [Business Analytics, SQL, Python, Tableau, Machine Learning]
---

In this project, we analyzed over **527,000 e-commerce transactions** from a UK-based online retailer to uncover sales patterns, identify high-value customers, and recommend data-driven strategies for inventory and marketing optimization.

The project demonstrates how business analytics tools such as **SQL, Python, Tableau, and statistical analysis** can transform raw transaction data into actionable insights.

# Table of Contents

- [00. Project Overview](#overview-main)
    - [Context](#overview-context)
    - [Actions](#overview-actions)
    - [Results](#overview-results)
    - [Growth / Next Steps](#overview-growth)
- [01. Data Overview](#data-overview)
- [02. Analytical Approach](#analysis-methods)
- [03. Key Insights](#analysis-insights)
- [04. Data Visualization](#visualizations)
- [05. Business Recommendations](#recommendations)
- [06. Limitations & Future Work](#limitations)

___

# 00. Project Overview <a name="overview-main"></a>

### Context <a name="overview-context"></a>

E-commerce businesses generate large volumes of transaction data, but without proper analysis this information provides little value for strategic decision making.

The goal of this project was to analyze historical transaction data from a UK-based online shop in order to understand:

* Which products generate the most revenue  
* How customer purchasing behavior varies  
* Which countries generate the most sales  
* Whether seasonal demand patterns exist  
* Which products underperform and waste inventory space  

Understanding these patterns allows the business to optimize both **marketing strategy and operational efficiency**.

---

### Actions <a name="overview-actions"></a>

To address these questions we performed several stages of analysis:

* Cleaned and prepared the raw dataset
* Performed descriptive statistical analysis
* Identified product performance patterns
* Conducted geographic and seasonal trend analysis
* Built dashboards and visualizations
* Evaluated classification models in Weka

The project used a combination of analytical tools:

* **SQL** – Data querying and aggregation  
* **Python** – Data processing and exploratory analysis  
* **Tableau / Power BI** – Data visualization dashboards  
* **Excel / R** – Descriptive statistical analysis  
* **Weka** – Classification models  

---

### Results <a name="overview-results"></a>

The analysis revealed several key findings:

* Revenue is heavily concentrated in the **holiday season**, particularly November.
* Approximately **35% of customers purchase in bulk**, suggesting a strong B2B segment.
* A large number of products generate very little demand.
* A small number of products dominate overall sales volume.
* Sales are highly concentrated in the **United Kingdom**, with smaller secondary markets abroad.

These insights led to several operational and strategic recommendations.

---

### Growth / Next Steps <a name="overview-growth"></a>

Future improvements to this project could include:

* Incorporating **multi-year sales data** for stronger trend analysis
* Implementing **predictive forecasting models**
* Integrating **customer behavior analytics**
* Developing automated reporting dashboards

These improvements would help transform the analysis into a **continuous decision-support system**.

___

# 01. Data Overview <a name="data-overview"></a>

The dataset contains **527,764 e-commerce transactions** collected over a **13-month period**.

Key characteristics of the dataset include:

* Transactions from **38 different countries**
* **3,768 unique products**
* Both **individual customers and bulk buyers**

### Key Variables

| Variable | Description |
|---|---|
| Transaction ID | Unique identifier for each purchase |
| Date | Date of transaction |
| Product ID | Unique product identifier |
| Product Name | Name of item purchased |
| Price | Unit price (£) |
| Quantity | Number of units purchased |
| Customer ID | Unique customer identifier |
| Country | Customer location |

Negative quantity values indicated **cancelled transactions**, which were considered during analysis.

___

# 02. Analytical Approach <a name="analysis-methods"></a>

The analysis followed several structured steps.

### Data Cleaning

Before performing analysis, the dataset was cleaned to address:

* Missing values
* Incorrect data types
* Categorical vs numerical formatting

Fortunately, the dataset contained relatively few inconsistencies.

---

### Statistical Analysis

Descriptive statistics were used to understand pricing and purchasing behavior.

For example:

* Average product price was approximately **£4.65**
* Some products had price outliers above **£110**
* Purchase quantities varied significantly between customers

This variation suggested both **individual buyers and bulk purchasing behavior**.

---

### Machine Learning Models

Several classification models were tested using Weka.

**OneR Model**

* Approximately **90% classification accuracy**
* However, the model was strongly biased toward the majority class.

**ZeroR Model**

* Produced a correlation coefficient of **0**
* Demonstrated no predictive capability.

These results suggested that the available features were not well suited for classification tasks.

___

# 03. Key Insights <a name="analysis-insights"></a>

### Seasonal Sales Patterns

Sales activity peaked in **November**, followed by a decline in December.

This pattern aligns with **holiday shopping behavior**.

Implication:

* Inventory planning and marketing campaigns should begin **well before the holiday season**.

---

### Customer Segmentation

Analysis of purchasing behavior revealed two distinct customer types:

* Individual consumers purchasing small quantities
* Bulk buyers purchasing large quantities for resale

Bulk buyers accounted for a **significant share of total revenue**.

---

### Product Performance

A small number of products dominated overall sales.

Top selling items included:

* Popcorn Holder
* WWII Gliders (Toy Planes)
* Jumbo Red Bag

Meanwhile, **156 products were sold only once** during the 13-month period.

These items likely consume inventory space without generating meaningful revenue.

---

### Geographic Distribution

Sales were heavily concentrated in:

1. United Kingdom  
2. Netherlands  
3. Germany  

Although the business sells internationally, most revenue comes from the UK market.

This suggests strong brand recognition domestically but **limited global penetration**.

___

# 04. Data Visualization <a name="visualizations"></a>

To better interpret the results, several dashboards and visualizations were developed.

Dashboards included:

* Monthly sales trends
* Cancellation patterns
* Top 10 countries by revenue
* Top-selling products by quantity
* Daily average sales trends

These visual tools help transform raw data into **clear operational insights for business leaders**.

___

# 05. Business Recommendations <a name="recommendations"></a>

Based on the analysis, several strategic recommendations were developed.

1. Launch marketing campaigns before the Q4 peak season.
2. Implement bulk pricing incentives for B2B buyers.
3. Remove persistently low-performing SKUs.
4. Deploy predictive forecasting models for inventory planning.
5. Automate executive dashboards for real-time reporting.
6. Integrate web analytics tools to better understand customer behavior.

These changes could significantly improve both **profitability and operational efficiency**.

___

# 06. Limitations & Future Work <a name="limitations"></a>

While the project produced valuable insights, several limitations should be considered.

* Only **13 months of historical data** were available.
* Customer feedback or satisfaction metrics were not included.
* Market trends and competitor activity were not analyzed.

Future research should incorporate **longer historical datasets and customer behavior data** to improve forecasting accuracy and strategic planning.

___
