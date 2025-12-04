# 🛒 Walmart Sales Analysis – End-to-End Data Analytics Project

This project analyzes **9,969 Walmart sales transactions** to uncover insights about **sales performance, customer behavior, profitable categories, payment trends**, and overall business performance.  
It follows a complete **Data Analytics Lifecycle** using **Python, SQL, and Power BI**.

---

## 📦 Project Overview

The goal of this project is to answer key business questions such as:

- Which branches and product categories generate the most revenue?
- What payment methods are most preferred by customers?
- Which months drive the highest sales and profit?
- How do customer ratings relate to product performance?
- What actions can Walmart take to increase revenue and customer satisfaction?

The workflow is divided into three major phases:

1. **Data Preparation (Python)**
2. **Data Analysis (SQL)**
3. **Visualization & Reporting (Power BI)**

---

## 🔧 Tools & Technologies

- **Python** – Data cleaning and preprocessing (`pandas`, `numpy`)
- **SQL (MySQL / PostgreSQL)** – Business logic and analytical queries
- **Power BI Desktop** – Interactive dashboards and KPIs
- **Excel** – Initial data review and validation

---
# 🛒 Walmart Sales Data Analysis

An end-to-end data analysis project focusing on **Walmart Sales Data** to derive actionable business insights and strategic recommendations. This project covers data cleaning with Python, analysis with SQL, and visualization with Power BI.

---

## 🛠️ Project Stack

| Category | Tool / Language | Files Used |
| :--- | :--- | :--- |
| **Data Cleaning & Prep** | Python (Pandas, NumPy) | `project.ipynb` |
| **Data Analysis** | SQL (MySQL / PostgreSQL) | `MySQL Queries.sql`, `PSQL Queries.sql` |
| **Data Visualization** | Power BI | `Walmart_Sales_Dashboard.pbix` |
| **Final Dataset** | CSV | `walmart_clean_data.csv` |

---

## 1. 🧹 Data Preparation (Python)

All data preparation and cleaning steps were performed in the `project.ipynb` notebook.

### Key Tasks:

* Cleaned **inconsistent values** and standardized **column names**.
* Converted price-related fields into **numeric format**.
* Created a new calculated field for total sales:
    ```python
    total = quantity * unit_price
    ```
* Exported the final clean dataset as `walmart_clean_data.csv`.

---

## 2. 🧠 Data Analysis (SQL)

A comprehensive analysis was performed using SQL scripts to answer core business questions.

### Business Questions Answered:

* Total transactions and total revenue.
* Quantity sold per payment method.
* Highest-rated categories by branch.
* Month-wise sales trend and busiest shopping days.
* Profitability analysis by category and city.
* Revenue comparison across years.
* Shift analysis (Morning / Afternoon / Evening) to understand peak shopping times.

---

## 3. 📊 Power BI Dashboard

Two interactive dashboards were created in Power BI to visualize the key findings.

### 📍 Dashboard 1 → Sales Overview
| Metric / Visualization | Highlight |
| :--- | :--- |
| **KPIs** | Total Sales, Profit, Quantity Sold, Average Rating |
| **Sales Trend** | Weekday sales trend by month |
| **Comparison** | Category-wise quantity comparison |
| **Profit Trend** | Profit by year |



### 📍 Dashboard 2 → Sales & Product Insights
| Metric / Visualization | Highlight |
| :--- | :--- |
| **Highest Selling Month** | December |
| **Top Revenue Category** | Fashion Accessories |
| **Trend** | Monthly revenue trend |
| **Profit** | Profit by top 5 cities |
| **Visualization** | Category profit visualization |



---

## 🔍 Insights & Findings

Key takeaways derived from the data analysis:

* **Top Performers:** **Fashion** and **Home Lifestyle** categories show the highest sales and profit contributions.
* **Payment Preference:** **E-wallet** is the most commonly used payment method.
* **Seasonal Peak:** **November** and **December** (holiday time) show a significant peak in customer demand and sales revenue.
* **Customer Loyalty:** **Subscribers** purchase more frequently than regular customers.
* **Key Demographic:** The **25–45 age group** drives the most revenue contribution.

---

## 💡 Strategic Recommendations

| Strategy | Expected Impact |
| :--- | :--- |
| **Promote High-Performing Categories** (e.g., Fashion, Home Lifestyle) | +10–15% seasonal revenue growth |
| **Boost Digital Payment Rewards** (e.g., E-wallet) | Higher conversion rate and increased sales volume |
| **Strengthen Subscription Program** | More repeated customers and higher Customer Lifetime Value (CLV) |
| **Combo Offers on Low Performers** | Achieve balanced category growth |
| **Seasonal Inventory Planning** | Avoid overstock and shortage during peak months |

---

## 🧭 Future Enhancements

Potential areas for future work and expansion:

* Implement **sales forecasting** using Machine Learning models.
* Perform **Market-Basket Analysis** to identify product associations.
* Conduct **Customer Segmentation** using clustering techniques.
* Set up automated dashboard refresh and data pipeline.


## 📂 Project Structure

```text
Walmart-Sales-Analysis
│── project.ipynb                     # Python notebook for cleaning & EDA
│── walmart_clean_data.csv            # Cleaned dataset
│── MySQL Queries.sql                 # SQL queries for insights (MySQL)
│── PSQL Queries.sql                  # SQL queries for insights (PostgreSQL)
│── Walmart Sales Analysis.pdf        # Final report with insights
│── Walmart_Sales_Dashboard.pbix      # Power BI dashboard file
│── README.md                         # Documentation
│── /images                           # Dashboard screenshots
│     ├── Sales & Product Insights.png
│     ├── Walmart Sales Overview.png
