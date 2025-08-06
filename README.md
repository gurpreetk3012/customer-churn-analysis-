# Customer Churn Analysis

This project focuses on analyzing customer churn behavior using exploratory data analysis and feature-specific insights. The goal is to identify patterns and key factors that influence a customer's decision to discontinue service. By examining demographic attributes, service usage, and account information, this analysis provides actionable insights that businesses can use to improve customer retention strategies.

## Methodology

### Data Exploration
- Verified absence of missing values.
- Analyzed feature distributions including `MonthlyCharges`, `TotalCharges`, and `tenure`.
- Identified that numerical ranges could influence churn likelihood.

### Churn Distribution
- Class distribution:
  - Churned customers: ~49.28%
  - Non-churned customers: ~50.71%
- The data is relatively balanced and suitable for classification modeling without extensive resampling.

### Feature-Level Insights
- Customers using **Fiber Optic** internet show higher churn rates (32.47% of churned users).
- High `MonthlyCharges` is positively correlated with churn.
- Customers without services like OnlineSecurity or TechSupport are more likely to churn.

### Customer Segmentation
- Segmented customers based on their behavioral and financial characteristics.
- Profiles identified include:
  - High-risk churners with high monthly charges and shorter tenure.
  - Long-tenured loyal customers.
  - Inactive or low-engagement customers with basic services.

## Business Implications

- Customers with shorter tenure and higher monthly charges are at higher risk of churn.
- Specific services like TechSupport and OnlineSecurity reduce churn probability.
- Targeted campaigns can be designed for customers on monthly contracts or those using Fiber Optic connections.

## How to Run

`Python 3.8` or higher and a `Jupyter Notebook` or `JupyterLab` environment are required to run the analysis.
