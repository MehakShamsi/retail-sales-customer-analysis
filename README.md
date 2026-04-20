# retail-sales-customer-analysis
Analyzed UK retail transactional data using Python, SQL, and Power BI to uncover insights on revenue trends, customer behavior, and product performance. Identified seasonal patterns, customer retention drivers, and high-return categories to support data-driven decision-making.

# Retail Sales & Customer Insights Analysis

## Project Overview
This project analyzes UK-based online retail data to uncover insights related to sales performance, customer behavior, and product trends.

The objective was to:
- Increase revenue
- Improve customer retention
- Optimize product strategy

---

## Key Business Questions

### Sales Analysis
- What are the monthly revenue trends?
- Which products generate the most revenue?

### Customer Analysis
- Who are the most valuable customers?
- What is the repeat purchase rate?

### Product Insights
- Which products drive revenue?
- Which categories have high return rates?

---

## Tools Used
- Python (Data Cleaning & Feature Engineering)
- SQL (Data Analysis)
- Power BI (Dashboard & Visualization)

---

## Data Preparation

- Handled missing values in CustomerID and Description
- Converted UK datetime format (DD/MM/YYYY) into ISO format
- Identified returns using negative quantities
- Created a **Product Category feature** using keyword-based classification

---

## Key Insights

### 1. Revenue & Seasonality
- Total revenue: £8.3M
- Peak in November (£1.13M) due to seasonal demand

### 2. Product Performance
- Top 10 products contribute only 8.18% of revenue
- Indicates a highly diversified product portfolio

### 3. Customer Behavior
- 69.96% of customers are repeat buyers
- Top 10 customers contribute 16.5% of revenue

### 4. Returns Analysis
- Certain categories (Kitchen & Lighting) show higher return rates
- Indicates potential quality or expectation mismatch

### 5. Geographic Insights
- UK contributes 81.5% of revenue
- International markets show growth potential

---

## Dashboard

![Dashboard](images/dashboard.png)

---

## Challenges Faced

- CSV import issues due to datetime format mismatch
- Data type issues when converting datetime in Python
- Lack of product categorisation in dataset

---

## Key Learning

- Importance of data preprocessing before analysis
- Difference between datetime storage vs display format
- Feature engineering significantly improves analysis quality
- Dashboard design is as important as analysis

---

## Project Files

- `retail_dashboard.pbix` → Power BI dashboard
- `project_documentation.pdf` → Detailed explanation
- `dashboard.png` → Dashboard preview

---

## Contact

Open to feedback and opportunities in Data Analytics.
