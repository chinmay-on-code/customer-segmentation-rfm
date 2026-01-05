# 📊 Customer Segmentation Using RFM Analysis
## 📌 Project Overview

### Understanding customer behavior is critical for effective marketing, retention, and revenue growth. This project applies RFM (Recency, Frequency, Monetary) analysis on real-world retail transaction data to segment customers into meaningful groups such as Champions, Loyal Customers, and At-Risk Customers.

### The outcome enables data-driven decision-making by identifying high-value customers, retention opportunities, and churn risks.

# 🎯 Business Objective

### The business lacks visibility into customer purchasing behavior and customer lifetime value. Without segmentation:

### High-value customers are not prioritized

### Marketing efforts remain generic

### Retention and re-engagement strategies are inefficient

# Goal:
## Segment customers based on purchasing behavior and monetary contribution to support targeted marketing, retention strategies, and revenue optimization.

# 📂 Dataset Information

## Dataset: Online Retail II

## Time Period: 2010–2011

## Data Type: Transaction-level retail data

## Source: Kaggle

# Key Columns

## Invoice

## InvoiceDate

## Customer ID

## Quantity

## Price

## Country

# 🛠 Tools & Technologies

## Python

## Pandas

## NumPy

## Data Visualization

## Tableau / Excel / Matplotlib

## Optional

## SQL (for aggregation logic)

# 🔍 Methodology
# 1. Data Loading & Exploration

### Loaded Excel-based transactional data

### Reviewed data structure, types, and missing values

### Identified cancellations, returns, and invalid records

# 2. Data Cleaning & Preparation

### Removed records with missing Customer IDs

### Excluded returns and negative transactions

### Converted invoice dates to datetime format

### Created total transaction value per invoice

# 3. RFM Metric Calculation

### A snapshot date was defined as one day after the last recorded transaction.

## For each customer:

### Recency: Days since last purchase

### Frequency: Number of unique invoices

### Monetary: Total amount spent

# 4. RFM Scoring

### Customers were ranked using quartile-based scoring (1–4)

### A combined RFM Score was generated for segmentation

# 5. Customer Segmentation

### Customers were grouped into business-relevant segments using RFM logic:

## Champions

## Loyal Customers

## At-Risk Customers

## Others

# 📊 Analysis & Visualizations

### Segment-level analysis was conducted to evaluate:

### Number of customers per segment

### Revenue contribution by segment

### Average purchase frequency

## Visuals Created:

### Customer distribution by segment

### Revenue contribution by segment

### Spending distribution across segments

# 💡 Key Insights

### A small percentage of customers generate a disproportionately large share of revenue

### High-frequency and recent customers are critical to revenue stability

### At-risk customers show declining engagement and require targeted reactivation

# 📈 Business Recommendations

### Introduce loyalty and VIP programs for high-value customers

### Launch re-engagement campaigns for at-risk segments

### Use personalized offers to increase lifetime value of loyal customers

# 🧠 STAR Method Summary

## Situation: Limited visibility into customer value and behavior

## Task: Segment customers based on purchasing behavior

## Action: Applied RFM analysis using Python and transactional data

## Result: Identified high-value and churn-risk customer segments to enable targeted marketing strategies
