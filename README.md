# Project Title: Customer Churn Analysis Dashboard
Interactive Power BI dashboard analyzing customer retention and churn patterns using demographic, service, and contract-related factors for actionable business insights.

# Description
A comprehensive Power BI dashboard analyzing a dataset of 7,043 customers to identify drivers of churn. The analysis focused on key variables including tenure buckets, contract types, internet service providers (Fiber optic vs. DSL), payment methods, and citizen types. By leveraging interactive visuals and slicers, the project highlights high-risk customer segments, enabling the business to transition from reactive to proactive retention strategies.

# Power BI Project Tools & Components
Power BI Desktop: Primary tool used for report canvas design and building the multi-page analytical interface.
Power Query: Utilized for data transformation, including the creation of Tenure Buckets (New, 1–2 Years, 3–4 Years, Loyal) to segment the customer base.
DAX (Data Analysis Expressions): Implemented to calculate core metrics such as Churn Rate %, Total Charges, and Customer Distribution across various dimensions.
Data Modeling: Structured the relationship between customer demographics and service attributes to ensure seamless cross-filtering and accurate reporting.

# Features & Highlights
Interactive Tenure & Service Slicers: Allows for granular filtering by customer loyalty levels and internet service types to pinpoint exactly where revenue is being lost.
Service-Level Churn Analysis: A Treemap and Bar chart breakdown showing a significant churn concentration in Fiber Optic users.
Payment Method Tracking: Visualized the correlation between manual payment methods (Electronic Check) and higher churn rates compared to automatic transfers.
Contract Type Comparison: Detailed breakdown of Month-to-month vs. Long-term contracts to illustrate the impact of contract flexibility on customer exits.

# Business Problem
The company was experiencing a 26.54% churn rate, resulting in significant revenue leakage (16.06M in Total Charges at risk). Management lacked visibility into whether churn was driven by service quality, billing friction, or demographic trends. HR and Sales teams needed a data-driven tool to identify "at-risk" customers—specifically new users—to implement targeted loyalty programs and contract incentives.
