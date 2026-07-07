# E-Commerce Customer Intelligence and Operational Performance Dashboard

An end-to-end Business Intelligence project that analyzes one million synthetic e-commerce transactions using Python and Power BI to uncover customer purchasing behavior, revenue drivers, and operational performance insights.

## Dashboard Preview

![Executive Overview](images/executive_overview.png)

## Project Overview
This project analyzes a synthetic Amazon-like e-commerce dataset containing **1,000,000 transaction records** to uncover customer purchasing patterns, revenue drivers, and operational factors affecting business performance.

Using **Python** for data cleaning, exploratory data analysis (EDA), and customer segmentation, and **Power BI** for interactive dashboard development, the project transforms raw transactional data into actionable business insights that can support strategic decision-making.

A key component of the analysis is **Recency, Frequency, and Monetary (RFM) segmentation**, which classifies customers into meaningful groups based on their purchasing behavior. The project also evaluates sales performance, product returns, shipping efficiency, and customer value to identify opportunities for revenue growth and operational improvement.

## Business Objectives
The primary objectives of this project were to:

- Analyze overall sales performance and revenue trends.
- Identify the highest-performing product categories.
- Segment customers using the RFM (Recency, Frequency, Monetary) framework.
- Measure the revenue contribution of each customer segment.
- Evaluate product return rates and operational performance.
- Identify opportunities to improve customer retention and business performance through data-driven insights.

## Dataset
The analysis was conducted using a **synthetic Amazon-like E-Commerce dataset** obtained from **Kaggle**. The dataset was designed to simulate realistic customer purchasing behavior, product information, seller performance, and order fulfillment processes in an online marketplace.

### Dataset Summary

- **Source:** [Amazon E-Commerce Dataset (Kaggle)](https://www.kaggle.com/datasets/sharmajicoder/amazon-e-commerce)
- **Dataset Type:** Synthetic E-Commerce Transactions
- **Number of Records:** 1,000,000
- **Number of Features:** 20
- **Time Period:** Transactions spanning the last two years

### Key Features

The dataset includes information on:

- Customer IDs
- Product Categories and Subcategories
- Brands
- Product Pricing and Discounts
- Customer Ratings and Reviews
- Seller Ratings
- Purchase Dates
- Shipping Time
- Customer Location
- Device Used
- Payment Method
- Product Returns
- Delivery Status

> **Note:** This dataset is synthetic and was created for analytical and educational purposes. It does not contain real Amazon customer or transaction data.

## Project Workflow
The project followed a structured analytics workflow consisting of the following stages:

### 1. Data Understanding

- Explored the dataset structure and data types.
- Examined all 20 variables.
- Assessed data quality and identified potential issues.

### 2. Data Preparation

- Converted data into appropriate formats.
- Created additional features required for analysis.
- Prepared the dataset for exploratory analysis and visualization.

### 3. Exploratory Data Analysis (EDA)

Performed exploratory analysis to answer key business questions, including:

- Which product categories generate the most revenue?
- What is the overall product return rate?
- How does revenue vary across customer segments?
- Which operational factors influence product returns?
- How do shipping performance and seller ratings relate to returns?

### 4. Customer Segmentation

Applied **Recency, Frequency, and Monetary (RFM)** analysis to segment customers into:

- High Value
- Loyal
- Potential
- Low Value

These segments were used to evaluate customer value and revenue contribution.

### 5. Dashboard Development

Designed an interactive Power BI dashboard consisting of three pages:

- Executive Overview
- Customer Intelligence
- Operations & Returns

The dashboard was built to enable stakeholders to monitor business performance and support data-driven decision-making.

## Dashboard Walkthrough
### 1. Executive Overview

The Executive Overview page provides a high-level summary of the business, enabling decision-makers to quickly monitor revenue, customers, order volume, return rates, sales trends, and category performance.

**Key Metrics**

- Total Revenue
- Total Orders
- Total Customers
- Average Order Value
- Return Rate

**Visuals Included**

- Monthly Revenue Trend
- Revenue by Category
- Customer Segment Distribution
- Average Revenue per Customer by Segment

![Executive Overview](images/executive_overview.png)

### 2. Customer Intelligence

This page focuses on customer behavior and value by leveraging RFM segmentation. It helps identify which customer groups generate the most revenue and highlights the platform's highest-value customers.

**Visuals Included**

- Customer Segment Distribution
- Revenue Contribution by Segment
- Average Revenue per Customer
- Top 10 Customers by Revenue

![Customer Intelligence](images/customer_intelligence.png)

### 3. Operations & Returns

The Operations & Returns page evaluates operational performance by analyzing return rates, shipping efficiency, seller performance, and delivery outcomes. It highlights operational factors that may influence customer satisfaction and product returns.

**Visuals Included**

- Return Rate by Category
- Shipping Time vs Return Rate
- Seller Rating vs Return Rate
- Delivery Status Distribution

![Operations & Returns](images/operations&returns.png)

## Key Insights
The analysis revealed several important business insights:

### 📈 Revenue Performance

- Electronics was the highest-performing product category, contributing approximately **66% of total revenue**.
- Revenue was distributed almost evenly across customer devices (Mobile App, Web, and Tablet), indicating balanced platform usage.

### 👥 Customer Intelligence

- High Value customers contributed approximately **51.5% of total revenue** despite representing only about **25%** of the customer base.
- High Value and Loyal customers together generated more than **88% of total revenue**, highlighting the importance of customer retention.
- Average customer revenue increased significantly across the customer segments, with High Value customers generating the highest average spend.

### 🚚 Operational Performance

- The overall product return rate was **11.6%**.
- Orders delivered in **6 days** experienced a return rate of approximately **20.7%**, nearly double the return rate for deliveries completed within 1–5 days.
- Seller ratings showed minimal influence on product returns, suggesting that shipping performance has a greater impact on customer satisfaction than seller reputation.

## Business Recommendations
Based on the findings, the following recommendations are proposed:

1. **Strengthen Customer Retention**
   - Invest in loyalty programs and personalized marketing campaigns to retain High Value customers, who generate over half of the platform's revenue.

2. **Increase Customer Lifetime Value**
   - Develop targeted promotions aimed at converting Loyal customers into High Value customers through personalized product recommendations and incentives.

3. **Improve Delivery Performance**
   - Reduce delivery times where possible, particularly for orders approaching six days, to help minimize product returns and improve customer satisfaction.

4. **Prioritize High-Performing Categories**
   - Continue investing in Electronics while identifying opportunities to improve the performance of lower-revenue categories through pricing, promotions, or product assortment.

5. **Monitor Operational KPIs**
   - Continuously track shipping performance, return rates, and customer segments using the dashboard to support timely, data-driven decision-making.

## Tools & Technologies
| Category | Tools |
|----------|-------|
| Programming Language | Python |
| Data Analysis | Pandas, NumPy |
| Data Visualization | Matplotlib |
| Business Intelligence | Power BI |
| Query & Modeling | DAX |
| Development Environment | Jupyter Notebook |
| Version Control | GitHub |
| Dataset Source | Kaggle |

## Repository Structure
```text
ecommerce-customer-intelligence-dashboard
│
├── data
│   └── dataset_description.md
│
├── images
│   ├── executive_overview.png
│   ├── customer_intelligence.png
│   └── operations&returns.png
│
├── notebooks
│   └── ecommerce_analysis.ipynb
│
├── powerbi
│
├── README.md
├── LICENSE
└── .gitignore
```

## How to Reproduce the Analysis
1. Clone this repository to your local machine.

2. Download the dataset from Kaggle:
   - https://www.kaggle.com/datasets/sharmajicoder/amazon-e-commerce

3. Open the Jupyter Notebook located in the `notebooks` folder.

4. Install the required Python libraries if they are not already installed.

5. Run the notebook to perform data cleaning, exploratory data analysis, feature engineering, and RFM segmentation.

6. Open the Power BI report (...) or review the dashboard screenshots included in the `images` folder.

## Project Limitations
- The dataset is synthetic and does not represent actual Amazon customer or transaction data.
- Some relationships observed in the analysis may not fully reflect real-world business behavior.
- The Power BI report file is not included in this repository because it exceeds GitHub's file upload size limit.

## About the Author
**Chinomso Nnorom**

Data Analyst with a background in Statistics, passionate about transforming data into actionable business insights through analytics, visualization, and storytelling.

### Connect with Me

- LinkedIn: *https://www.linkedin.com/in/chinomso-nnorom-74458522a/*
- Portfolio: *http://nomso.lovable.app/*
- Email: *nnoromchinomso2019@gmail.com*
