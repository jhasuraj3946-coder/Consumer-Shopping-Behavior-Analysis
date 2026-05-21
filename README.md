# Consumer Shopping Behavior Analysis

## Project Overview

This project analyzes customer shopping behavior using transactional retail data containing approximately 3,900 purchase records across multiple product categories.

The objective of this project is to identify customer purchasing trends, revenue-driving segments, discount dependency, subscription behavior, and product performance in order to support data-driven business decisions.

The project demonstrates an end-to-end data analytics workflow involving:

- Data preprocessing and feature engineering using Python
- Business analysis using SQL and PostgreSQL
- Interactive dashboard development in Power BI
- Business recommendations based on analytical insights

---

## Business Problem Statement

Retail businesses generate large amounts of customer transaction data every day. Understanding this data is essential for improving customer engagement, increasing sales, and optimizing marketing strategies.

This project aims to answer key business questions such as:

- Which customer groups contribute the highest revenue?
- How do discounts affect purchasing behavior?
- Are subscription users more valuable than non-subscribers?
- Which products perform best across categories?
- What factors influence repeat purchases and customer loyalty?

---

## Dataset Information

| Attribute | Details |
|---|---|
| Total Records | 3900 |
| Total Features | 18 |
| Domain | Retail / E-Commerce |
| Database | PostgreSQL |

### Key Features

- Customer demographics
- Product categories
- Purchase amount
- Subscription status
- Discount usage
- Shipping preferences
- Review ratings
- Seasonal purchase trends

---

## Technologies Used

- Python
- Pandas
- NumPy
- PostgreSQL
- SQL
- Power BI
- Matplotlib
- Seaborn
- GitHub

---

## Project Workflow

### 1. Data Cleaning and Preprocessing

Performed preprocessing using Python:

- Handled missing values
- Standardized column names
- Removed redundant features
- Created customer age groups
- Engineered purchase frequency features
- Verified data consistency

### 2. Exploratory Data Analysis

Performed EDA to understand customer behavior patterns:

- Purchase distribution analysis
- Customer segmentation
- Revenue analysis
- Product category trends
- Subscription behavior analysis

### 3. SQL Business Analysis

Business-oriented SQL queries were written in PostgreSQL to analyze:

- Revenue by gender
- High-spending discount users
- Top-rated products
- Shipping type comparison
- Subscription analysis
- Discount dependency
- Customer segmentation
- Revenue contribution by age group

### 4. Power BI Dashboard

Developed an interactive dashboard to visualize:

- Revenue trends
- Customer segments
- Category-wise sales
- Revenue by age group
- Subscription insights
- Average review ratings

---

## Key Insights

- Male customers generated significantly higher overall revenue.
- Customers using express shipping showed higher average purchase values.
- Loyal customers represented the majority of total purchases.
- Fashion-related products showed strong discount dependency.
- Young adult customers contributed the highest revenue among all age groups.

---

## Business Recommendations

- Strengthen loyalty programs for repeat buyers.
- Promote subscription memberships using targeted campaigns.
- Optimize discount strategies for high-discount product categories.
- Focus marketing efforts on high-revenue customer groups.
- Prioritize top-rated products in promotional campaigns.

---

## Project Structure

```text
Consumer-Shopping-Behavior-Analysis/
│
├── Problem_statement/
├── Report/
├── python/
├── Dashboard img
├── sql/
├── dataset/
├── README.md
