# Churn-analysis

Project Overview
This project focuses on analyzing customer churn using a telecom dataset. By exploring various features like account length, international and voice mail plans, call usage, and customer service interactions, I identified patterns related to churn. Tableau was used to create visualizations that provide key insights into churn rates, customer behavior, and service usage.

Dataset
The dataset contains the following columns:

State: US state where the customer resides.
Account length: Number of days the customer has been with the company.
Area code: Customer's area code.
International plan: Whether the customer has an international plan (Yes/No).
Voice mail plan: Whether the customer has a voice mail plan (Yes/No).
Number vmail messages: Number of voice mail messages.
Total day minutes, Total day calls, Total day charge: Daytime call duration, count, and charges.
Total eve minutes, Total eve calls, Total eve charge: Evening call duration, count, and charges.
Total night minutes, Total night calls, Total night charge: Nighttime call duration, count, and charges.
Total intl minutes, Total intl calls, Total intl charge: International call duration, count, and charges.
Customer service calls: Number of customer service interactions.
Churn: Whether the customer churned (True/False).

Project Workflow

Churn Rate Pie Chart:

Created a pie chart to visualize the overall churn rate.
Churn rate results: 14.24% of customers have churned, while 85.76% have not churned.
Account Length Binning:

Divided customers into bins based on account length to visualize the distribution.
The majority of customers have an account length between 60-130 days, with most churns occurring within this range. After 130 days, customer retention improves, and churn rates decline.
Churn by International and Voice Mail Plans:

Created a column chart comparing churned and non-churned customers based on their subscription to international and voice mail plans.
Customers with an international plan were more likely to churn, while the voice mail plan had little correlation with churn.

State-wise Analysis:

Visualized the sum and average of international, night, and day calls and charges for each state, color-coded by churn.
Identified churn patterns based on state-wise usage of services like international and night calls. States with higher churn rates showed higher international call usage.

State vs. Churn Rate:

Created a state-wise churn map to show churn rates across different US regions.

Dashboard Creation:

Combined all insights into an interactive dashboard to provide a comprehensive view of churn drivers and service usage patterns.

Conclusions
Churn Rate: 14.24% of customers have churned, with the highest churn occurring in the 60-130 day account length range.
Account Length: Customers who have been with the company longer (above 130 days) tend to have lower churn rates, indicating better retention for long-term customers.
International Plans: Customers with international plans are more likely to churn, suggesting a potential area for service improvement or targeted retention strategies.
Geographical Insights: States with higher churn tend to have higher international call usage, indicating that state-specific churn strategies might be needed.

Requirements
Tableau for visualization
