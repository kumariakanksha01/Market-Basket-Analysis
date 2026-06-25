# Purchase Pattern Analytics using Market Basket Analysis

## Project Overview

This project analyzes retail transaction data to uncover customer purchasing patterns using Market Basket Analysis (MBA) and the Apriori Algorithm. The objective is to identify products that are frequently purchased together and transform these insights into actionable business recommendations for product bundling, cross-selling, and shelf placement optimization.

The solution includes data cleaning, exploratory data analysis (EDA), association rule mining, recommendation generation, and interactive dashboarding using Power BI.

---

## Business Problem

Retail businesses process thousands of customer transactions daily but often struggle to identify hidden relationships between products.

Understanding which products are frequently purchased together can help businesses:

* Increase average basket size
* Improve cross-selling opportunities
* Optimize store layout and shelf placement
* Design effective promotional campaigns
* Enhance customer shopping experience

---

## Project Objectives

* Perform exploratory analysis on retail transaction data
* Clean and transform raw transactional data
* Generate frequent itemsets using the Apriori Algorithm
* Discover association rules using support, confidence, and lift metrics
* Identify product bundling opportunities
* Recommend cross-sell strategies
* Build an interactive Power BI dashboard for business users

---

## Dataset Information

### Source

Retail Transaction Dataset

### Features

| Column       | Description           |
| ------------ | --------------------- |
| BillNo       | Unique Invoice Number |
| Itemname     | Product Name          |
| Quantity     | Quantity Purchased    |
| Present_Date | Transaction Date      |
| Price        | Unit Price            |
| CustomerID   | Customer Identifier   |
| Country      | Customer Country      |

---

## Project Workflow

### 1. Data Ingestion

* Imported transaction dataset using Pandas
* Standardized column names and formats
* Validated data types

### 2. Data Cleaning

* Removed duplicate transactions
* Handled missing values
* Removed cancelled invoices
* Standardized date formats
* Investigated quantity and pricing anomalies
* Validated transaction integrity

### 3. Exploratory Data Analysis

* Transaction volume analysis
* Product frequency analysis
* Basket size analysis
* Country-level transaction analysis
* Outlier detection

### 4. Data Transformation

Created a Transaction × Product Matrix:

Invoice → Product Purchased

Converted quantities into binary values:

* 1 = Product Purchased
* 0 = Product Not Purchased

---

## Market Basket Analysis

### Frequent Itemset Generation

Applied Apriori Algorithm to identify frequently purchased product combinations.

### Association Rule Mining

Generated rules using:

* Support
* Confidence
* Lift


---

## Recommendation Framework

Association rules were categorized into:

### Bundle Opportunities

Products frequently purchased together and suitable for bundled promotions.

### Cross-Sell Opportunities

Products recommended during checkout or online purchase journeys.

### Shelf Placement Recommendations

Products with strong affinity that should be placed near each other in stores.

---

## Power BI Dashboard

### Dashboard Features

* Executive KPI Cards
* Product Affinity Analysis
* Recommendation Table
* Product Bundle Opportunities
* Cross-Sell Scatter Plot
* Product Affinity Heatmap
* Recommendation Distribution Analysis

### Key Metrics

* Total Rules Generated
* Average Lift
* Average Confidence
* Strong Bundle Count
* Product Affinity Score

---

## Key Insights

* Identified strong product associations through lift-based analysis
* Discovered high-confidence cross-selling opportunities
* Generated actionable product bundling recommendations
* Revealed customer purchasing behavior patterns
* Enabled data-driven merchandising decisions

---

## Tools & Technologies

### Programming

* Python
* SQL

### Python Libraries

* Pandas
* NumPy
* Matplotlib
* MLxtend

### Visualization

* Power BI

### Analytics Techniques

* Exploratory Data Analysis (EDA)
* Market Basket Analysis
* Apriori Algorithm
* Association Rule Mining
* Customer Purchase Behavior Analysis

---

## Repository Structure

```text
Purchase-Pattern-Analytics/
│
├── data/
│   └── processed/
│
├── notebooks/
│   └── Market_Basket_Analysis.ipynb
│
├── dashboard/
│   └── Purchase_Pattern_Analytics.pbix
│
├── reports/
│   ├── Project_Presentation.pptx
│   
│
├── outputs/
│   ├── frequent_itemsets.csv
│   ├── association_rules.csv
│   └── recommendation_dashboard.csv
│
├── README.md

```

---

## Business Impact

This project demonstrates how data analytics can be used to convert raw retail transaction data into actionable business recommendations that support revenue growth, customer engagement, and merchandising optimization.

---

## Author

Akanksha Kumari

Data Analytics | Business Intelligence | Power BI | SQL | Python

