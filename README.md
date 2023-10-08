# Alteryx-Project-Ecommerce-Transaction-Cohort-Analysis
Exploring E-commerce Transactions: Data Cleaning, Cohort Analysis, and Business Insights generation using Alteryx Designer Core. 

# Alteryx Project: Customer Transaction Analysis

## Project Description
This Alteryx workflow is designed to perform comprehensive analysis on customer transactions using the provided dataset. The project encompasses three main phases:
1.Data Cleaning
2.Cohort Analysis
3.Business Insights Generation.

## Dataset: `trasaction_dataset.csv`
The project utilizes the `trasaction_dataset.csv` dataset, which contains detailed information about customer transactions, including transaction IDs, product details, customer IDs, dates, and order statuses, among others. This dataset was sourced from Hicounsellor.com/projects titled"Analyzing E-commerce Transactions:Data Cleaning, Cohort Analysis, and SQL". This CSV contains 20,000 rows across 13 columns.

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

## Phases

### Phase 1 - Data Cleaning
In this phase, the following steps were performed:
1. **Filtered out undesired columns:** Identified and eliminated extraneous columns not necessary for analysis such as "product_class" and "product_size using SELECT tool
2. **Data Type Conversion:** Ensured data types were compatible for analysis using SELECT tool
3. **Renamed Columns:**Revamped column names to enhance clarity using SELECT tool
4. **Quality Assurance:** Checked for data integrity and corrected any discrepancies.

For a detailed view of the Data Cleaning process, refer to the [Alteryx Workflow (.yxmd)](link_to_yxmd_file).

### Phase 2 - Cohort Analysis
This phase involved the following steps:
1. **Customer Segmentation:** Grouped customers into cohorts based on their transaction behavior.
2. **Cohort Metrics:** Calculated key metrics (e.g., retention rate, average spend) for each cohort.
3. **Visual Representation:** Generated visualizations to aid in cohort comparison.

For a detailed view of the Cohort Analysis process, refer to the [Alteryx Workflow (.yxmd)](link_to_yxmd_file).

### Phase 3 - Business Insights Generation
The final phase encompassed the following steps:
1. **Distinct Brands:** Identified unique brands available in the dataset.
2. **Unique Customers:** Counted the number of unique customers who made transactions.
3. **Approved vs. Unapproved Orders:** Quantified approved and unapproved transactions.
4. **Average List Price by Product Line:** Listed top product lines with the highest average list price.
5. **Top 5 Profitable Products:** Identified products with the highest profit margin.
6. **Customer Spending Analysis:** Evaluated customer transactions, including total spend and average profit per transaction.
7. **Top 5 Product Lines by Revenue Contribution:** Identified product lines with the highest total revenue contribution.
8. **Customers Who Purchased from All Product Lines:** Identified customers with transactions in all product lines.

For a detailed view of the Business Insights Generation process, refer to the [Alteryx Workflow (.yxmd)](link_to_yxmd_file).

---

Feel free to explore the Alteryx workflows for each phase for a deeper understanding of the data processing and analysis. For any questions or further assistance, please don't hesitate to reach out.

**Project Created By: [Roopmathi Gunna]**
**Date: [10-06-2023]**

---

*Note: Replace `[link_to_yxmd_file]`, `[Your Name]`, and `[Date]` with the actual links and information.*

