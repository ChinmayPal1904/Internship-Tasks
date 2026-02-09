# Task 1

# Business Sales Performance Analytics

## 📌 Project Overview
This project analyzes e-commerce sales data to identify revenue trends,
top-performing products, and key geographical markets. The goal is to
provide data-driven insights that can help businesses improve decision-making.

## 🎯 Objectives
- Identify top revenue-generating products
- Analyze sales trends over time
- Understand country-wise revenue contribution
- Provide actionable business insights

## 📂 Dataset
- Type: E-commerce transactional data
- Records: 541,909 transactions
- Time Period: Dec 2010 – Dec 2011
- Key Fields:
  - InvoiceNo
  - Description
  - Quantity
  - UnitPrice
  - InvoiceDate
  - Country

## 🛠️ Tools & Technologies
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Google Colab

## 🔄 Data Preparation
- Removed missing values
- Converted date columns to datetime format
- Revenue calculated using:


## 📊 Analysis Performed
- Key business KPIs calculation
- Top 10 products by revenue
- Country-wise revenue analysis
- Monthly revenue trend analysis

## 🔍 Key Insights
- A small number of products generate the majority of revenue
- Sales show strong seasonal patterns
- United Kingdom is the dominant revenue contributor
- Revenue is highly concentrated in specific products

## 💡 Business Recommendations
- Focus inventory and promotions on top-performing products
- Strengthen marketing strategies during peak seasons
- Explore controlled international expansion

## ▶️ How to Run the Notebook
1. Open the notebook in Google Colab
2. Upload the dataset CSV file
3. Run all cells sequentially

## 📬 Contact
Created as part of **Data Science & Analytics Internship – Task 1**



# 📊 Task 2: Customer Churn Analysis (Power BI)

## 📌 Project Overview

Customer churn analysis focuses on identifying customers who are likely to stop using a company’s products or services. In **Task 2**, this analysis is performed using **Power BI**, emphasizing **interactive dashboards, visual storytelling, and business insights** rather than coding.

This task is part of an **Internship Task Series** and demonstrates how **Power BI dashboards** can be used to analyze churn behavior and support data-driven decision-making.

---

## 🎯 Objectives

* Understand the concept of customer churn
* Analyze churn patterns using Power BI visuals
* Identify key factors influencing customer churn
* Build interactive dashboards for business users
* Derive actionable insights to improve customer retention

---

## 🧾 Dataset Description

The dataset contains customer-level information such as:

* Customer ID
* Gender
* Senior Citizen
* Tenure (in months)
* Services subscribed (Phone, Internet, etc.)
* Contract Type
* Monthly Charges
* Total Charges
* Churn Status (Yes / No)

> 📌 *The dataset is cleaned and transformed using Power BI Power Query.*

---

## 🛠️ Tools & Technologies Used

* **Power BI Desktop**
* **Power Query Editor** (for data cleaning)
* **DAX** (basic calculated measures)

---

## 🔄 Workflow

1. **Data Import** – Load customer churn dataset into Power BI
2. **Data Cleaning** – Handle missing values and data types using Power Query
3. **Data Modeling** – Create relationships and calculated columns
4. **DAX Measures** –

   * Total Customers
   * Churned Customers
   * Churn Rate (%)
5. **Dashboard Creation** – Build interactive visuals
6. **Insight Generation** – Interpret churn trends

---

## 📊 Dashboards & Visuals Created

* Overall Customer Churn Rate (KPI Card)
* Churn Distribution (Bar / Pie Chart)
* Tenure vs Churn Analysis
* Contract Type vs Churn
* Monthly Charges vs Churn
* Interactive slicers (Gender, Contract Type, Services)

---

## 📈 Key Insights

* Customers on **month-to-month contracts** have the highest churn rate
* **Low-tenure customers** are more likely to churn
* Higher **monthly charges** increase churn probability
* Long-term contracts improve customer retention

---

## 📁 Project Structure

```
Task-2-Customer-Churn-PowerBI/
│
├── dataset/
│   └── customer_churn.csv
│
├── powerbi/
│   └── Task_2(Data Science).pbix
│
├── screenshots/
│   └── dashboard_view.png
│
└── README.md
```

---

## 🚀 How to Use the Dashboard

1. Download the `.pbix` file
2. Open it in **Power BI Desktop**
3. Use slicers to filter data
4. Explore visuals to understand churn patterns

---

## 📌 Conclusion

This Power BI project highlights how interactive dashboards can effectively analyze customer churn and support strategic business decisions. The insights derived can help organizations improve customer satisfaction and retention.

---

## ✍️ Author

**Chinmay Pal**
