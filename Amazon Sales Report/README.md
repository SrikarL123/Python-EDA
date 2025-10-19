
---

# 🛒 Amazon Sales Data Analysis

## 📘 Project Overview

This project focuses on analyzing Amazon sales data to understand product trends, customer preferences, and overall sales distribution.
The process includes **data cleaning** and **exploratory data analysis (EDA)** using Python in Google Colab.

---

## 📂 Files in This Repository

| File                       | Description                                                        |
| -------------------------- | ------------------------------------------------------------------ |
| `Amazon Sales Report.csv`  | Raw dataset containing unprocessed Amazon sales data.              |
| `Amazon_Sales_Cleaned.csv` | Cleaned dataset after fixing missing values and formatting issues. |
| `ASR_Colab.ipynb`   | Colab notebook with complete EDA workflow.                         |
| `README.md`                | Project documentation.                                             |

---

## ⚙️ Project Steps

### **1️⃣ Data Loading**

The raw Amazon dataset was imported using Pandas and examined for structure, missing values, and inconsistencies.

### **2️⃣ Data Cleaning**

* Removed duplicates and null values
* Standardized column names and formats
* Converted data types for accuracy
* Exported the cleaned data as `Amazon_Sales_Cleaned.csv`

### **3️⃣ Exploratory Data Analysis (EDA)**

Key analyses performed using Matplotlib and Seaborn visualizations:

Order Status Distribution – Count of each order status category

Top 10 Product Categories – Visualized highest-selling categories

Order Amount Distribution – Checked spread and skew of order amounts

Outlier Detection – Used boxplots to identify extreme order values

Correlation Heatmap – Analyzed relationships between numeric features

Monthly Sales Trend – Observed variation of total sales across months

Fulfillment Type Distribution – Compared different fulfillment modes

Amount vs Fulfillment Relationship – Boxplot analysis between order type and amount
---

## 💡 Key Insights

* Cleaning improved data quality and reduced inconsistencies.
* Clear patterns appeared in product categories and yearly trends.
* IMDb rating distribution highlighted varying performance across types.

---
