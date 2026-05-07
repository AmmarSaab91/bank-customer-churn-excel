# Bank Customer Churn Analysis — Excel Project

## Project Overview

This project analyzes bank customer churn using Microsoft Excel. The goal is to identify which customer groups are more likely to leave the bank and provide business recommendations to improve customer retention.

The analysis was completed using Excel formulas, Excel Tables, PivotTables, PivotCharts, and a dashboard.

## Dataset

The dataset contains **10,000 bank customers**.

The target column is `exited`:

* `1` = churned customer
* `0` = retained customer

Main customer attributes analyzed include:

* Country
* Gender
* Age group
* Credit score group
* Tenure
* Number of products
* Active membership status
* Credit card ownership
* Balance
* Estimated salary

## Tools Used

* Microsoft Excel
* Excel Tables
* PivotTables
* PivotCharts
* Dashboard KPIs
* Structured references
* Conditional grouping formulas

## Key Metrics

|Metric|Value|
|-|-:|
|Total Customers|10,000|
|Churned Customers|2,038|
|Retained Customers|7,962|
|Overall Churn Rate|20.38%|

## Dashboard Summary

The dashboard summarizes the main churn indicators using KPI cards and charts.

Main dashboard elements:

* Total customers
* Churned customers
* Retained customers
* Overall churn rate
* Churn rate by country
* Churn rate by gender
* Churn rate by age group
* Churn rate by credit score group
* Churn rate by tenure
* Churn rate by number of products

## Key Insights

### 1\. Germany has the highest churn risk

Germany shows the highest churn rate among the countries. Although France has the largest customer base, Germany produces almost the same number of churned customers with a smaller customer base.

This suggests that Germany is the highest-risk market.

### 2\. Inactive customers are more likely to churn

Inactive customers have a much higher churn rate than active customers. This shows that customer engagement is strongly related to retention.

### 3\. Number of products is an important churn indicator

Customers with 2 products have the lowest churn rate, while customers with 3 or 4 products show very high churn rates.

This may indicate dissatisfaction, product complexity, or unsuitable product combinations for some customers.

### 4\. Older customers show higher churn risk

Churn increases in older age groups, especially after age 40. This suggests that older customers may require more targeted retention strategies.

### 5\. Female customers have a higher churn rate

Female customers show a higher churn rate than male customers in this dataset. This makes gender a useful segmentation variable for further churn analysis.

### 6\. Credit score and tenure are weaker indicators

Credit score groups and tenure do not show as strong a churn pattern as country, activity status, age, or number of products.

## Business Recommendations

Based on the analysis, the bank should focus retention efforts on:

1. German customers, because they have the highest churn risk.
2. Inactive customers, because lack of engagement is strongly connected to churn.
3. Older customers, especially customers above 40.
4. Customers with only 1 product, because they represent a large share of churned customers.
5. Customers with 3 or 4 products, because their churn rate is unusually high.

Recommended actions:

* Create targeted retention campaigns for German customers.
* Improve engagement with inactive customers.
* Offer personalized product reviews for customers with many products.
* Investigate why older customers are leaving.
* Build loyalty offers for high-risk customer segments.

## Limitations

This analysis is based on a static dataset, so it identifies patterns but does not prove causation.

Some customer groups, such as customers with 4 products, may have small sample sizes, so their churn rates should be interpreted carefully.

A future improvement could include building a machine learning model to predict churn risk at the individual customer level.

## Project Files

Recommended workbook structure:

* `Customer-Churn-Records`: cleaned customer data
* `validation`: data quality checks
* `EDA`: analysis tables and PivotTables
* `dashboard`: visual dashboard
* `Insights`: final written business analysis

## Conclusion

The analysis shows that customer churn is strongly associated with country, activity status, age, and number of products. The most important business priority is to reduce churn among German customers, inactive customers, older customers, and customers with risky product usage patterns.

## AUTHOR

Ammar Saab



