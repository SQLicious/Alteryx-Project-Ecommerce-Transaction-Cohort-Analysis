# Project Overview

Embark on a informational journey through my Alteryx project,designed to enhance e-commerce operations. This project has three vital stages: Data Cleanup, Cohort Analysis, and Insights generation. Together, we'll unravel the nuances of online shopping, driving strategic decisions to maximize revenue.

This project draws inspiration from Hicounsellor's 'Analyzing E-commerce Transactions'. However, I've taken a unique approach by exclusively utilizing Alteryx Designer. This showcases the remarkable efficiency of low-code solution such as Alteryx , offering a fresh perspective on streamlining processes and extracting actionable insights for business professionals.

Quick Alteryx Workflow Demo Before Diving Into the Project Details


# Table of Contents

1. Dataset: `transaction_dataset.csv`
2. Data Cleanup
3. Cohort Analysis
4. Insights Generation
5. Project Inspiration
6. Methodology
7. Upcoming Additions


# 1. Dataset{#dataset}

- [Download Dataset](https://github.com/SQLicious/Alteryx-Project-Ecommerce-Transaction-Cohort-Analysis/blob/main/1.%20Inputs/transaction_dataset.csv)

The project utilizes the `trasaction_dataset.csv` dataset, which contains detailed information about customer transactions, including transaction IDs, product details, customer IDs, dates, and order statuses, among others. This dataset was sourced from Hicounsellor.com/projects titled *"Analyzing E-commerce Transactions:Data Cleaning"*. This CSV contains 20,000 rows across 13 columns.

## Data Profile

The dataset provides the following key attributes:

- Transaction ID
- Product ID
- Customer ID
- Transaction Date
- Online Order (True/False)
- Order Status (Approved/Unapproved)
- Brand
- Product_Line
- List Price
- Standard Cost
- Product First Sold Date

# Phases

This Alteryx workflow is designed to perform comprehensive analysis on customer transactions using the provided dataset. The project encompasses three main phases:
1.Data Cleaning
2.Cohort Analysis
3.Business Insights Generation.

## 2. Phase 1- Data Cleanup {#data-cleanup}

In this phase, the following steps were performed:
1. **Filtered out undesired columns:** Identified and eliminated extraneous columns not necessary for analysis such as "product_class" and "product_size using SELECT tool
2. **Data Type Conversion:** Ensured data types were compatible for analysis using SELECT tool
3. **Renamed Columns:**Revamped column names to enhance clarity using SELECT tool
4. **Quality Assurance:** Checked for data integrity using temporary BROWSE tool

## 3. Phase 2 - Cohort Analysis {#cohort-analysis}

This phase involved the following steps:
1. **Customer Segmentation:** Grouped customers into cohorts based on their transaction behavior.
2. **Cohort Metrics:** Calculated key metrics (e.g., retention rate, average spend) for each cohort.
3. **Tabular Representation:** Generated Cohort Retention rate to aid in cohort comparison.

For a detailed view of the Cohort Analysis process, refer to the [Alteryx Workflow (.yxmd)](https://github.com/SQLicious/Alteryx-Project-Ecommerce-Transaction-Cohort-Analysis/blob/main/3.%20Workflows/Phase%201-2-3.yxmd)
...

## 4. Phase 3 Insights Generation {#insights-generation}
The final phase encompassed the following steps:
1. **Unique Brands**: Identifying the variety of products and manufacturers present in the sales records to understand market presence.

2. **Unique Customers**: Assessing the extent of the customer base for segmentation and targeted marketing efforts.

3. **Approved vs. Unapproved Orders**: Evaluating the success rate of transactions to improve operational efficiency.

4. **Top Product Lines by List Price**: Identifying high-revenue product categories for pricing and marketing strategies.

5. **High-Profit Margin Products**: Identifying products with significant profit margins for pricing decisions.

6. **Average List Price by Product Line**: Understanding pricing trends within different product categories.

7. **Brand with Maximum Price Margin**: Identifying brands with the potential for higher profit margins.

8. **Customer Transactions Count**: Providing insights into customer behavior and loyalty.

9. **Total Sales by Brand**: Identifying top-performing brands in terms of revenue generation.

10. **Top 5 Profitable Products**: Pinpointing the most profitable products in inventory.

11. **Customer Transaction Metrics**: Analyzing customer transaction history, expenditure, and average profitability.

12. **Top Product Lines by Revenue**: Understanding which product lines drive significant sales and revenue.

13. **Customers Across all Product Lines**: Identifying customers engaged with the entire product range.


For a detailed view of the Business Insights Generation process, refer to the [Alteryx Workflow (.yxmd)](https://github.com/SQLicious/Alteryx-Project-Ecommerce-Transaction-Cohort-Analysis/blob/main/3.%20Workflows/Phase%201-2-3.yxmd).


## 5. Project Inspiration {#project-inspiration}

This project draws inspiration from Hicounsellor's 'Analyzing E-commerce Transactions'. However, I've taken a unique approach by exclusively utilizing Alteryx Designer. This showcases the efficiency of low-code solutions such as Alteryx Designer, offering a fresh perspective on streamlining processes and extracting actionable insights, even by a non-technical business user.

## 6. Methodology {#methodology}
In this project, I leveraged the skills and knowledge acquired during the Alteryx Designer Core certification and the pursuit of four microcredentials. This allowed me to harness a robust set of Alteryx tools, putting them to work in a cohesive workflow.

Throughout this project, I harnessed the full potential of Alteryx, seamlessly executing all phases. Leveraged a range of powerful tools from each tool palette
- **In/Out Tools:**
  - Input
  - Output

- **Preparation Tools:**
  - Data Cleansing
  - Filter
  - Formula
  - Multi-Field
  - Sample
  - Select
  - Sort
  - Unique

- **Join Tools:**
  - Append
  - Join

- **Transform Tool Palette:**
  - Cross-Tab
  - Summarise


I ensured an efficient data transformation process. This would have taken me 3 weeks (120 man hours using the SQL and Python approach) and i built this worklow in 3 days.
This comprehensive utilization of Alteryx highlights its remarkable capabilities in ETL( Extract - Load - Transformation)

## 7. Upcoming Additions {#upcoming-additions}

I plan to automate the generation of a comprehensive PDF report combining Phase 2 cohort analysis results with answers to 13 business questions. This report will be sent automatically to a designated list of recipients. Additionally, I'm exploring the possibility of exporting Phase 2 cohort analysis data to Tableau using the Tableau output feature.


**Project Created By: [Roopmathi Gunna]**
**Date: [10-06-2023]**

---


