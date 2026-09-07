# 🛵 E-Commerce Quick-Commerce Delivery Analytics

## 📌 Project Overview

This project performs an **Exploratory Data Analysis (EDA)** on a simulated E-Commerce Quick-Commerce Delivery dataset containing **100,000 orders** across three major quick-commerce platforms:

- Swiggy Instamart
- Blinkit
- JioMart

The analysis focuses on understanding **delivery performance, order values, customer satisfaction, delivery delays, and refund behaviour** using Python-based data analysis and visualization techniques.

The project applies **Univariate, Bivariate, and Multivariate Analysis** to identify meaningful patterns and business insights.

---

## 🎯 Objectives

The main objectives of this project are:

- Load and inspect the raw dataset.
- Identify and handle missing values and duplicate records.
- Validate data types and prepare the dataset for analysis.
- Analyze individual variables using univariate analysis.
- Explore relationships between variables using bivariate analysis.
- Perform multivariate analysis to identify combined patterns.
- Understand customer satisfaction and service ratings.
- Analyze delivery delays and their relationship with ratings.
- Investigate refund request behaviour.
- Generate business-oriented insights from the analysis.

---

## 📊 Dataset

The dataset contains **100,000 records and 11 columns**, with each row representing one delivery order.

### Dataset Details

| Metric | Value |
|---|---:|
| Total Records | 100,000 |
| Total Columns | 11 |
| Platforms | 3 |
| Product Categories | 6 |
| Unique Customers | 9,000 |
| Delivery Time | 5–76 minutes |
| Order Value | ₹50–₹2,000 |
| Service Rating | 1–5 |

### Columns

| Column | Description |
|---|---|
| `Order ID` | Unique identifier for each order |
| `Customer ID` | Unique customer identifier |
| `Platform` | Delivery platform |
| `Order Date & Time` | Timestamp of order placement |
| `Delivery Time (Minutes)` | Time taken to deliver the order |
| `Product Category` | Category of product ordered |
| `Order Value (INR)` | Total order value |
| `Customer Feedback` | Customer feedback/comment |
| `Service Rating` | Customer rating from 1 to 5 |
| `Delivery Delay` | Whether the order was delayed |
| `Refund Requested` | Whether a refund was requested |

---

## 🛠️ Tools & Technologies

- **Python 3**
- **Pandas** – Data loading, cleaning and manipulation
- **NumPy** – Numerical operations
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical visualization
- **Jupyter Notebook / Python**
- **GitHub** – Project hosting and documentation

---

## 🔄 Project Workflow

```text
Raw Dataset
     ↓
Data Loading & Inspection
     ↓
Data Cleaning & Preprocessing
     ↓
Univariate Analysis
     ↓
Bivariate Analysis
     ↓
Multivariate Analysis
     ↓
Insight Generation
     ↓
Business Recommendations
