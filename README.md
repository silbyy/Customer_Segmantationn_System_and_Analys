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
