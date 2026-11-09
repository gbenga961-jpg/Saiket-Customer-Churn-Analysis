# Customer Churn Analysis

## Project Overview

This project analyses customer churn in a telecommunications business using Python. The objective is to understand customer behaviour, identify patterns associated with customer attrition, and develop practical business recommendations that could support customer retention.

This project was completed as part of my Business Analysis Internship at Saiket Systems.

## Business Problem

Customer churn can affect business revenue, customer relationships and long-term growth. Understanding the patterns associated with customer departures can help businesses develop more effective retention strategies.

This analysis explores customer demographics, contract types, payment methods, tenure and billing patterns to identify customer segments with higher churn rates.

## Project Objectives

- Understand the structure and characteristics of the dataset.
- Investigate missing values, whitespace-only entries and duplicates.
- Clean and prepare the data for analysis.
- Explore customer behaviour and churn patterns.
- Analyse relationships between customer tenure, contracts, payment methods and charges.
- Identify high-risk customer segments.
- Translate analytical findings into actionable business recommendations.

## Dataset Overview

The dataset contains 7,043 customer records and 21 original columns.

It includes customer demographics, subscription information, services, contract details, payment methods, tenure, billing information and churn status.

Two additional analytical features, `tenure_group` and `monthly_charge_segment`, were created during the analysis.

## Tools and Technologies

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Git and GitHub

## Project Workflow

### 1. Dataset Understanding

- Examined dataset dimensions, columns and data types.
- Reviewed descriptive statistics.
- Investigated missing values and duplicate records.
- Identified 11 whitespace-only entries in `TotalCharges`.

### 2. Data Cleaning and Preparation

- Standardised column names.
- Converted whitespace-only `TotalCharges` entries into proper missing values.
- Converted `TotalCharges` to a numeric data type.
- Validated the cleaned dataset.

### 3. Exploratory Data Analysis

Investigated churn patterns across:

- Gender and senior citizen status.
- Contract types.
- Payment methods.
- Customer tenure.
- Monthly and total charges.

### 4. Customer Segmentation and Advanced Analysis

Created tenure and monthly-charge segments to investigate differences in customer behaviour and churn rates.

## Key Findings

| Customer Segment | Churn Rate |
|---|---:|
| Month-to-month contracts | 42.71% |
| One-year contracts | 11.27% |
| Two-year contracts | 2.83% |
| Tenure: 0–12 months | 47.44% |
| Tenure: 13–36 months | 25.54% |
| Tenure: 37+ months | 11.93% |
| Electronic check payment | 45.29% |

Additional findings:

- Senior citizens had a churn rate of 41.68%, compared with 23.61% for non-senior customers.
- Customers who churned had a higher median monthly charge (approximately $79.65) than customers who stayed (approximately $64.43).
- High monthly-charge customers had a churn rate of 34.09%.
- High-charge month-to-month customers recorded a churn rate of 52.61%.

## Business Recommendations

1. **Improve early customer retention:** Strengthen onboarding, customer support and engagement during the first 12 months.
2. **Encourage longer-term contracts:** Explore suitable incentives for month-to-month customers to consider longer contracts.
3. **Review payment experience:** Investigate the higher churn observed among electronic check users.
4. **Review high-charge customers:** Examine pricing competitiveness, service value and customer satisfaction.
5. **Apply targeted retention strategies:** Use customer segmentation to develop more relevant retention initiatives.

## Analytical Limitations

The analysis identifies relationships and patterns in the available dataset. These relationships do not independently establish causation. Additional customer feedback and business information would be needed to investigate the underlying reasons for churn.

## Repository Structure

```text
Saiket-Customer-Churn-Analysis/
│
├── .gitignore
├── Customer_Churn_Analysis.ipynb
└── README.md
```

## Key Learning Outcomes

- Data inspection and quality assessment.
- Data cleaning and preprocessing using Pandas.
- Exploratory data analysis.
- Data visualisation and interpretation.
- Customer segmentation.
- Business insight generation and recommendations.
- Git and GitHub version control.

## Acknowledgement

This project was completed as part of my Business Analysis Internship at Saiket Systems.

**Author:** Joshua Gbenga Ayobami

**Project:** Customer Churn Analysis

**Internship:** Saiket Systems – Business Analysis Internship