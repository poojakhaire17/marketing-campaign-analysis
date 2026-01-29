# 📊 Marketing Campaign Performance & Customer Acquisition Analysis


## 🔹 Business Context

- Marketing effectiveness depends on understanding how customer demographics, purchasing behavior, product preferences, sales channels, and promotional campaigns interact with each other.
- Using the marketing mix framework (People, Product, Place, Promotion), this project analyzes customer data to uncover the key drivers of customer acquisition and campaign success.
- The goal is to help marketing teams make data-driven decisions related to targeting, channel investment, and campaign optimization.

## 🔹 Business Objective

- The objective of this analysis is to:
- Understand customer demographics and spending behavior
- Identify factors influencing campaign response
- Analyze product and channel performance
- Validate marketing assumptions using statistical hypothesis testing
- Provide actionable insights to improve customer acquisition strategy

## 🔹 Dataset Overview

The dataset includes customer-level information related to:

### People

- Birth year
- Education
- Marital status
- Income
- Household composition

### Product

- Spending on wine, fruits, meat, fish, sweets, and gold products

### Place

- Purchases via store, web, and catalog channels

### Promotion

- Campaign acceptance indicators
- Complaints
- Campaign response behavior

## 🔹 Tools & Technologies

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- SciPy (Hypothesis Testing)
- Jupyter Notebook

## 🔹 Data Preparation & Feature Engineering

### Key preprocessing steps included:

- Validation and correction of date and income fields
- Missing income imputation using education level and marital status similarity
- Data cleaning of categorical variables

### Feature engineering:

- Customer age
- Total number of children at home
- Total spend across all product categories
- Total number of purchases across channels
- Outlier detection and treatment using distribution analysis

## 🔹 Exploratory Data Analysis

The following analyses were performed:

- Distribution analysis using histograms and box plots
- Correlation analysis using heatmaps
- Channel-wise and product-wise spending patterns
- Demographic segmentation based on age, education, family size, and geography

## 🔹 Hypothesis Testing

Statistical tests were conducted to validate common marketing assumptions:

1️⃣ Older customers prefer in-store shopping
2️⃣ Customers with children prefer online purchases
3️⃣ Alternative sales channels cannibalize in-store sales
4️⃣ Customers in the US outperform other countries in total purchases

Appropriate parametric and non-parametric tests were applied based on data distribution characteristics.

## 🔹 Key Insights

Customers with fewer or no children exhibit significantly higher total spending
Product categories such as wine and meat contribute disproportionately to total revenue
Channel preference varies across age groups, but older customers do not exclusively prefer in-store purchases
Minimal evidence of sales cannibalization between channels
Campaign response rates differ meaningfully by geography
Certain countries demonstrate consistently higher engagement with promotions

## 🔹 Business Recommendations

Focus marketing campaigns on high-value customer segments identified by age and household structure
Allocate promotional budgets toward top-performing product categories
Optimize channel investment based on demographic preferences rather than assumptions
Use geographic insights to tailor localized campaign strategies
Leverage campaign response patterns for targeted re-marketing initiatives

## 🔹 Deliverables

Cleaned and feature-engineered dataset
Exploratory analysis notebook
Statistical validation of business hypotheses
Visual storytelling charts
Insight summary for decision-makers

## 🔹 Sample Visualizations

Product revenue comparison
Channel-wise purchase behavior
Campaign response by age and country
Correlation heatmap

## ✅ Outcome & Impact

This project demonstrates how structured data analysis can be used to:
Improve customer segmentation
Optimize marketing channel investments
Enhance campaign targeting strategies
Support data-driven decision-making
The analysis showcases a complete workflow — from raw data preprocessing to insight generation and business recommendations.

## 📁 Repository Structure
marketing-campaign-analysis/

├── notebooks/
│   └── marketing_campaign_analysis.ipynb
│
├── images/
│   ├── product_revenue.png
│   ├── Country-acceptance.png
│   ├── Customer-Complaints.png
│
│
└── README.md

## 👩‍💻 Author

Pooja Khaire
Data Scientist | Data Engineer
Python • Data Analysis • Visualization • Tableau • GCP

## 📬 Contact

If you would like to collaborate or discuss a data analytics project, feel free to connect via:
Upwork Profile (link added on portfolio)
GitHub

⭐ If you found this project helpful, feel free to star the repository.
