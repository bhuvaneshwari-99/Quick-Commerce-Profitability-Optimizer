# Margin Console: Diagnosing Profit Leaks in Quick-Commerce
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
 
## 🔑 Key Insights

- **Loss is geographically concentrated, not category-driven.**
  Top 3 cities (Haridwar, Jaipur, Kolkata) account for **41.37%** of total losses — a classic Pareto/80-20 pattern. In contrast, product categories show near-uniform loss distribution (~14% each), indicating city-level operational issues, not a specific product line.

- **Delivery speed is the strongest profit lever — not delivery quality.**
  Orders delivered in 0-10 minutes are **~2x more profitable** than 31-40 minute orders, while delivery partner rating shows **negligible correlation with profit** (under 1% variance across ratings 2-5). This flips the intuitive assumption that "better-rated partners = better margins."

- **Discounting is broadly flat across customer segments.**
  Discount usage sits around **~40%** for every age group, with no single demographic disproportionately driving losses — ruling out age-targeted discount strategy as a quick fix.

- **Discounts and delivery costs erode ~21% of revenue** before it reaches net profit, based on the revenue-to-net-profit waterfall breakdown.

- **Payment method reveals a hidden risk pattern** *(pending 100%-stacked fix)* — Cash on Delivery orders may carry a disproportionately higher loss share versus digital payments, suggesting a COD-specific cost/risk exposure worth flagging operationally.
---
## 📬 Contact

Bhuvaneshwari L
📧 Email: lbhuvaneshwari729@gmail.com

🌐 LinkedIn: https://www.linkedin.com/in/bhuvaneshwaril/

💻 GitHub: https://github.com/bhuvaneshwari-99
