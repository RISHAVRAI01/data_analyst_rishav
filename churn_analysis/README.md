# Customer Churn Analysis

## Project Overview
Analyzed customer subscription data to understand churn behavior, customer retention, subscription plans, contract types, cancellation reasons, customer lifetime value (CLTV), and churn risk.

## Business Questions
- What is the overall customer churn rate?
- Which subscription plans have the highest churn rates?
- How does churn vary between monthly and annual contracts?
- What are the main reasons customers cancel their subscriptions?
- Which customers have the highest churn risk?
- How does churn risk relate to customer lifetime value (CLTV)?
- How much monthly revenue is at risk from churned customers?
- Which customers should be prioritized for retention efforts?
- What is the overall customer retention rate?

## Key KPIs
- Total Customers: 21
- Churned Customers: 6
- Churn Rate: 28.57%
- Retention Rate: 71.43%
- Average Monthly Charge: $18.85
- Total Customer Lifetime Value (CLTV): $17,294
- High-Risk Customers: 6
- Monthly Revenue at Risk: $73.94

## Key Insights
- The Basic plan had the highest churn rate at 60%, compared with 22.22% for Standard and 14.29% for Premium.
- Monthly contracts had a substantially higher churn rate than annual contracts, at 55.56% versus 8.33%.
- Switching to a competitor was the most common cancellation reason, accounting for 2 of the 6 churned customers.
- Other churn reasons included pricing, insufficient content, poor streaming quality, and forgetting to cancel a trial.
- Six customers had churn scores of 70 or above and were identified as high-risk customers.
- High-risk customers were prioritized using churn score and CLTV to identify customers requiring retention attention.
- Churned customers represented $73.94 in monthly recurring charges that are at risk.
- The analysis showed that customers on monthly contracts and lower-tier plans require greater retention attention.

## Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SQLite
