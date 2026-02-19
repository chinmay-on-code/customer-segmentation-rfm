## Customer Segmentation Using RFM Analysis
Data-Driven Customer Intelligence for Revenue Optimization

## Executive Summary
This project leverages RFM (Recency, Frequency, Monetary) analysis on real-world retail transactional data to build a scalable customer segmentation framework.

Using Python-based data analytics and business logic, customers were segmented into actionable cohorts such as Champions, Loyal Customers, and At-Risk Customers to support targeted marketing, retention strategies, and revenue optimization initiatives.

The analysis translates raw transaction-level data into strategic business insights, enabling improved customer lifetime value (CLV), churn mitigation, and marketing ROI enhancement.

## Business Problem
The organization lacked customer-level visibility into purchasing behavior and revenue contribution. As a result:

Marketing campaigns were generic and inefficient

High-value customers were not prioritized

Churn-risk customers were not proactively identified

Revenue concentration risk was not understood

### Key Business Question
 How can we segment customers based on behavioral and monetary patterns to enable data-driven decision-making and maximize profitability?

## Methodology
A structured, analytics-driven approach was followed:

### 🔹 Data Preparation & Cleaning

Removed missing customer identifiers

Excluded cancellations and negative transactions

Engineered total transaction value feature

Converted date fields for time-based analysis

### 🔹 Exploratory Data Analysis (EDA)

Analyzed transaction distribution

Evaluated missing data patterns

Assessed revenue spread and customer concentration

### 🔹 RFM Metric Engineering

For each customer:

Recency: Days since last purchase

Frequency: Number of unique purchase transactions

Monetary: Total customer spend

### 🔹 Scoring & Segmentation

Applied quartile-based scoring (1–4 scale)

Generated composite RFM score

Designed business-relevant segmentation logic

Segments Created:

Champions

Loyal Customers

At-Risk Customers

Others

### 🔹 Segment-Level Performance Analysis

Customer distribution analysis

Revenue contribution comparison

Behavioral trend assessment

## Skills
### Technical Skills
Python

Pandas

NumPy

Data Cleaning & Feature Engineering

Exploratory Data Analysis (EDA)

Customer Segmentation

RFM Modeling

Data Visualization (Excel / Tableau / Matplotlib)

Git & Version Control

### Analytical & Business Skills
Marketing Analytics

Customer Lifetime Value Analysis

Revenue Optimization Strategy

Data-Driven Decision Making

Stakeholder Communication

Business Insight Generation

## Results & Business Recommendation
### 🔎 Key Findings
![Customer Count Bar Chart](1.png)
![Revenue Contribution Chart](2.png)

A small percentage of customers contribute a disproportionately high share of revenue

High-recency, high-frequency customers drive revenue stability

At-risk customers show measurable decline in engagement

Revenue concentration indicates dependency on premium customer cohorts

### 📈 Strategic Recommendations
#### For Champions:

Implement VIP loyalty programs

Offer early access and personalized rewards

Strengthen relationship marketing

#### For Loyal Customers:

Upsell and cross-sell opportunities

Personalized retention campaigns

#### For At-Risk Customers:

Re-engagement email campaigns

Targeted discount offers

Churn prevention strategies

#### Expected Impact:

Improved customer retention

Increased marketing efficiency

Enhanced customer lifetime value

Optimized marketing spend allocation

## Next Steps
To further enhance analytical depth and business impact:

Integrate Customer Lifetime Value (CLV) modeling

Deploy SQL-based automation pipeline

Develop real-time segmentation dashboard

Incorporate campaign response data for uplift modeling

Implement predictive churn modeling
