# Telecom Customer Churn Analysis

## Project Overview
This project analyzes customer churn patterns in a telecom company using Python and Power BI. The objective is to identify the key factors influencing customer churn and provide business recommendations to improve customer retention.

## Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Power BI
- SQL Concepts

## Dataset
IBM Telco Customer Churn Dataset

The dataset contains customer demographic information, service details, contract information, billing details, and churn status.

## Data Cleaning
- Converted TotalCharges from object data type to numeric format.
- Identified and handled missing values.
- Verified data quality and consistency.

## Exploratory Data Analysis (EDA)

### Key Insights

### 1. Contract Type and Churn
- Month-to-month customers showed the highest churn rate (~43%).
- Customers with longer contracts were significantly more likely to stay.

### 2. Tenure and Churn
- Customers with low tenure had a higher probability of churn.
- Long-term customers showed better retention.

### 3. Internet Service and Churn
- Fiber optic customers experienced higher churn compared to DSL customers.
- This may indicate pricing or service-quality concerns.

### 4. Customer Demographics
- Senior citizens showed relatively higher churn rates.
- Customers without dependents tended to churn more frequently.
- Gender had minimal impact on churn behavior.

## Power BI Dashboard

The dashboard contains:

### Dashboard Page
- Total Customers KPI
- Total Churn KPI
- Churn Distribution

### Customer Churn Analysis
- Contract Type vs Churn
- Payment Method vs Churn
- Internet Service vs Churn
- Business Insights Summary

### Customer Demographics Analysis
- Gender vs Churn
- Senior Citizen vs Churn
- Dependents vs Churn
- Demographic Insights Summary

## Business Recommendations
- Encourage customers to move toward long-term contracts.
- Improve onboarding experience for new customers.
- Investigate churn among Fiber Optic customers.
- Develop targeted retention strategies for high-risk customer groups.

## Project Structure

```text
telecom-customer-churn-analysis/
│
├── churn_analysis.ipynb
├── Telecom Customer Churn Dashboard.pbix
├── README.md
├── dashboard.png
└── dataset/
```

## Dashboard Preview

Add your dashboard screenshot below:

```markdown
![Dashboard](dashboard.png)
```

## Author

**Dhivanya G**

Aspiring Data Analyst | Python | SQL | Power BI | Data Analytics
