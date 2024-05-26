# Churn Analysis 

## Introduction
In this churn analysis, we delve into customer retention dynamics for a fictional telco company operating in California during Q3. Our primary focus is on identifying customers at risk of leaving and understanding factors contributing to churn, a critical metric impacting revenue and customer satisfaction.

## Dataset
The dataset used for analysis is available [here](https://www.kaggle.com/datasets/shilongzhuang/telecom-customer-churn-by-maven-analytic).

## Main Dashboard
The main dashboard provides an overview of churned customers across categories, highlighting critical factors like revenue loss, leading churn-inducing services, and the number of customers at risk of churning.
//![Main Dashboard](https://example.com/assets/main.png)


## Risk of Churning Dashboard
Leveraging High-Value Score and Churn Risk Score, this dashboard analyzes customer distribution, revenue by risk category, and tenure category. It uses complex DAX queries dervied from the weights assigned in the correlation graph for all features vs a customer churning to calculate which customers are at risk of churning.

## Customer Demographics
Analyzing customer demographics such as gender, age, marital status, dependents, and referrals offers insights for targeted marketing strategies and customer segmentation, crucial for catering to specific age groups effectively.

## Revenue Dashboard
Insights into revenue loss from churned customers and potential revenue at risk from customers prone to churning are provided in the revenue dashboard. Key performance indicators and payment plan preferences enrich understanding of revenue dynamics.

## Services Dashboard
This dashboard evaluates the performance of phone and internet services offered by the telco company.

## Location Analysis
A location dashboard allows for comprehensive regional analysis, identifying geographical patterns in customer behavior, service preferences, and revenue generation.



## Final Insights and Conclusions
Key insights from the analysis include:
- Primary churn reasons: competitors' offerings, superior devices, and support quality.
- Factors contributing to churn: month-to-month contracts, specific offers, lack of online security, and non-utilization of premium tech support.
- Location-based analysis: San Diego shows the highest churn rate, suggesting the need for localized retention strategies.
- Customer demographics: Gender, marital status, age, and average monthly GB download have minimal impact on retention, emphasizing service quality and customer experience.
- Service-specific churn: Customers using fiber optic cable and streaming music services are more prone to churn.
  
## Recommendations
The report recommends:
- Enhancing service quality and products to remain competitive.
- Improving customer support experiences.
- Implementing targeted marketing strategies based on churn risk and high-value scores to reduce churn, retain valuable customers, and improve business performance and customer satisfaction.
