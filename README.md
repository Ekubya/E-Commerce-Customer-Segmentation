# E-Commerce Customer Segmentation & RFM Analysis 📊

![Dashboard Preview](E-commerce Customer Segmentation and RFM Analysis Dashboard.png)

## 📌 Project Overview
As an Industrial Engineering student, I analyzed a dataset of 500,000+ e-commerce transactions to solve a critical business problem: **Understanding customer retention and maximizing revenue through segmentation.**

Using **Power BI** and the **RFM (Recency, Frequency, Monetary)** technique, I transformed raw sales data into actionable business insights.

## 💼 Business Problem
The company faced challenges in identifying:
1. Who are the most valuable customers?
2. Which customers are at risk of churning?
3. How to optimize marketing budgets based on customer behavior?

## 🛠️ Technical Workflow & Tools
* **Data Cleaning (Power Query):** Handled null values, filtered cancelled orders (negative quantities), and fixed data types.
* **Data Modeling (DAX):** Created complex measures for `Recency`, `Frequency`, and `Monetary` scores.
    * *Example DAX for Frequency:* `DISTINCTCOUNT(CustomerID)`
* **Visualization:** Designed an interactive dashboard with dynamic slicers (Date & Country) and scatter plots to visualize the correlation between spend and frequency.

## 💡 Key Insights Derived
* **VIP Impact:** The top **9,24%** of customers (VIPs) contribute to **53,8%** of total revenue.
* **Retention Challenge:** **31.6%** of customers have only made a single purchase, indicating a need for a "Second Purchase" marketing campaign.
* **Market Dominance:** The **United Kingdom** is the dominant market, significantly outperforming other regions like Germany and France.

## 📂 Files in this Repository
*  E-commerce Segmentation and RFM Analysis.pbix : The complete Power BI file (download to view interactively).
*  raw data.zip : The dataset used for this project.
*  E-commerce Customer Segmentation and RFM Analysis Dashboard.png : Snapshot of the final dashboard.

---
*Author: Aybüke Altunbey | Industrial Engineering Graduate Candidate
