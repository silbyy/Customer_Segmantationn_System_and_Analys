# Customer_Segmantationn_System_and_Analys
AI-driven customer segmentation and predictive analysis system using K-Means clustering on 53,500+ insurance records

Customer Segmentation and Predictive Analysis System
This project implements a customer segmentation model using a dataset of 53,503 insurance customers. By applying the K-Means Clustering algorithm, the system categorizes customers into five distinct personas to optimize marketing strategies and product offerings.

Project Overview
The primary goal is to analyze customer demographics and financial behaviors (Age, Income Level, and Premium Amount) to identify patterns and provide automated product recommendations.

Methodology
Data Preprocessing: Standardization of features using StandardScaler.

Modeling: Unsupervised Learning via K-Means Clustering.

Evaluation: Segment distribution analysis and revenue contribution mapping.

Customer Personas Defined
Wealthy but Passive: High-income individuals with low current engagement.

Loyal Seniors: Older customers with consistent, long-term premium payments.

Prudent Middle-Income: Balanced earners looking for stability.

Elite Young Professionals: High-earning younger demographics.

Emerging Market: New and younger customers with growth potential.

Strategic Business Recommendations

Wealthy but Passive (Segment 0)

Why: This group has high income but their premium payments are lower than expected relative to their wealth. They are likely using basic services.

Strategy: Cross-selling.

Recommendation: Offer high-yield investment funds or private pension schemes. They have the capital; we need to provide the vehicle.

Loyal Seniors (Segment 1)

Why: Higher age and consistent premium history. This group values stability and has a long-term relationship with the brand.

Strategy: Retention and Estate Planning.

Recommendation: Focus on comprehensive life insurance and inheritance tax planning services. Keep them engaged with "loyalty rewards" to prevent churn to competitors.

Prudent Middle-Income (Segment 2)

Why: Average income and average age. These are the "backbone" of the customer base, likely with families.

Strategy: Bundling.

Recommendation: Home and family health insurance packages. Discounted "family bundles" will appeal to their budget-conscious but protective nature.

Elite Young Professionals (Segment 3)

Why: High income at a young age. They are tech-savvy, fast-paced, and have high spending power.

Strategy: Premium Digital Experience.

Recommendation: Private banking services, premium credit cards with travel benefits, and "pay-as-you-go" digital insurance products. They value time and status.

Emerging Market (Segment 4)

Why: Younger demographic with lower current income/premiums but high future potential.

Strategy: Acquisition and Growth.

Recommendation: Entry-level products like travel insurance, gadget insurance (phone/laptop), or education savings plans. The goal is to "hook" them early and upgrade them as their income grows.

Technical Stack
Language: Python

Data Analysis: Pandas, NumPy

Machine Learning: Scikit-learn

Visualization: Matplotlib, Seaborn

Key Features
HD Dashboard: Includes donut charts for population distribution and bar charts for revenue analysis.

Predictive Function: A built-in tool, analyze_new_customer(), that assigns segments and suggests products for new entries in real-time.

How to Run
The analysis is contained within the Jupyter Notebook file. Ensure all dependencies (pandas, sklearn, seaborn) are installed before execution.

License
This project is licensed under the MIT License.
