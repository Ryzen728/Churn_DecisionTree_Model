# Customer Loyalty
This project analyzes customer demographic and purchase history data to predict telecommunications customer churn.

## Project Overview
- The business leaders are interested in understanding customer loyalty at a high level.
- The company would benefit from the insights if it can use them retain customers.
- The final product is a machine learning model that would predict churn likelihood given demographic profile and contract history.

## Business / Research Problem
- A loss of customers means a loss of revenue, and ultimately, a loss of employment. T
- This analysis should inform the company's marketing strategy to retain more customers. 

## Datasets
- Dataset name: Telco-Customer-Churn.csv (given), see repository.
- 7043 rows/ 23 columns, data types: int64, objects, float64.
- Highly imbalanced data set, necessitating F1 testing for model accuracy evaluation.

## Key Questions / Objectives
- What factors impact a customer's decision to not renew their phone contract?
- Can we predict whether a customer will churn based on certain demographic factors and contract history?
- What are the key trends in telecommunications service provision?

## Results & Insights
- Main findings were that the features most influential to churn were: Tenure in months, having a month-to-month  contract, having a two-year contract, and not having dependents.

## Visualizations
- The analysis includes a decision tree classifier.
- ROC curve missing due to wrong data types in the true-positive rate data.

## Tools & Technologies
- Python packages (e.g., pandas, scikit-learn, seaborn, matplotlib, warnings)
- ML or visualization tools used

## Methodology
Outline your data science process:
- Data Cleaning & EDA: Counting and removing duplicates and null values
- Feature Engineering: Data scaling, column transformation, pipeline process structuring
- Modeling / Analysis: Train-Test Split, PCA, Decision Tree Classification
- Evaluation: Grid Search Cross Valiation, ROC Curve, ANOVA F-test
