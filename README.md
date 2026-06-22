# Quick_Commerce_Profitability_Optimizer
Data Analytics Project analyzing order-level profitability for quick-commerce platforms using SQL, Excel,Python (EDA,Statistical) and Power BI.
-

# 📊 Data Analytics Project

## 🧭 Overview

This project replicates a **real-world quick-commerce profitability analysis**, similar to work done by data analysts at companies like **Swiggy Instamart, Blinkit, Zepto, and BigBasket**.

It involves cleaning and exploring a **large-scale transactional dataset (1M+ records)**, running **SQL queries (PostgreSQL)** to uncover loss-making patterns, performing supporting analysis in **Excel**, and building an **interactive Power BI dashboard** to visualize profitability, delivery performance, and discount impact.

The goal is to identify which orders, products, and locations are losing money — and provide data-backed recommendations to improve margins.

---

## 📂 Dataset

* **Source:** [Quick Commerce Dataset – Kaggle](https://www.kaggle.com/datasets/rohitgrewal/quick-commerce-dataset)
* **Format:** CSV
* **Size:** ~1,000,000 records
* **Description:** Order-level data including customer, location, product category, basket value, delivery cost, discounts, delivery time, and customer rating.
* **Target Outcome:** Identify profitability drivers, loss-making segments, and actionable cost-optimization insights.

---

## ⚙️ Tools & Technologies
| Category                        | Tools Used                                 |
| ------------------------------- | ------------------------------------------ |
| Database                        | PostgreSQL                                 |
| SQL IDE                         | pgAdmin / DBeaver                          |
| Programming Language            | Python                                     |
| Python Environment              | Google Colab                               |
| Data Analysis                   | Pandas, NumPy                              |
| Statistics                      | Descriptive Statistics, Hypothesis Testing |
| Experimentation                 | A/B Testing                                |
| Exploratory Data Analysis (EDA) | Pandas, Matplotlib, Seaborn                |
| Data Cleaning                   | Excel, Power Query, Python                 |
| Data Visualization              | Power BI, Matplotlib, Seaborn              |
| Business Intelligence           | Power BI                                   |
| Spreadsheet Analysis            | Microsoft Excel                            |

---
# Key Insight
 Through SQL analysis of the dataset, the following key insights were identified:
## Profitability
 
- **7.84% of all orders are loss-making**, indicating a meaningful share of transactions actively erode margin rather than just underperforming.
- **Beverages (14.57%), Household (14.37%), and Groceries (14.30%)** are the three largest contributors to losses, together accounting for nearly 43% of total loss value.
- **Haridwar, Jaipur, and Amritsar** contribute **41.37%** of total losses, showing that profitability issues are concentrated in a small number of cities rather than spread evenly — a classic Pareto pattern.
- **Average profit drops by approximately 12.5%** as delivery distance increases, falling from **₹513.56** for orders within 0–2 KM to **₹449.25** for orders beyond 8 KM — a clear sign that longer deliveries quietly erode margin.
- **Discounted orders carry a distinctly different profit profile** than full-price orders, confirming that discounts boost order value at the cost of margin rather than improving profitability overall.
---
## 📬 Contact

**Author:** Bhuvaneshwari L
📧 Email: lbhuvaneshwari729@gmail.com

🌐 LinkedIn: https://www.linkedin.com/in/bhuvaneshwaril/

💻 GitHub: https://github.com/bhuvaneshwari-99
