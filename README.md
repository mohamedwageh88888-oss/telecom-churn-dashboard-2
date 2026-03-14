# 📞 Telecom Customer Churn Analysis Dashboard

![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Data Analytics](https://img.shields.io/badge/Data_Analysis-Project-blue?style=for-the-badge)
![Customer Retention](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

## 📋 Project Overview
This project presents a comprehensive **Customer Churn Analysis** for "Databel," a fictional telecommunications company. The dashboard is designed to identify key drivers of churn, analyze customer demographics, and provide actionable insights to improve retention strategies.

---

## 🚀 Key Performance Indicators (KPIs)
Based on the **Overview** analysis:
* 👥 **Total Customers:** 6,687
* 📉 **Total Churners:** 1,796
* 📊 **Churn Rate:** **26.86%**
* 📉 **Total Revenue:** ~$21M

---

## 🖼️ Dashboard Previews

### 1. 🔍 Executive Overview
*Visualizes the high-level churn rate and total customer count. It highlights the main reasons for churn, with **Competitors** being the primary driver (45%).*

### 2. 👥 Demographics Analysis
*Focuses on how age, gender, and group memberships affect churn. Key insight: **Senior citizens** and customers **not in a group plan** show significantly higher churn rates.*

### 3. 🌐 International & Data Usage
*Explores the relationship between international plans and data consumption. Customers with an **International Plan** but low international minutes have a high propensity to churn.*

---

## 🛠️ Built With
* **Power BI Desktop:** For data modeling and visualization.
* **DAX (Data Analysis Expressions):** For advanced measures like Churn Rate % and Revenue Loss calculations.
* **Power Query:** For data cleaning and transformation (ETL).
* **Dataset:** `Databel - Data.csv`

---

## 🧠 Key Insights & Findings

* **⚠️ Contract Type:** Customers on **Month-to-Month** contracts have a much higher churn rate compared to those on one-year or two-year plans.
* **📱 Data Usage:** Churn is higher among customers with low monthly GB downloads (under 5GB).
* **📍 Regional Trends:** Specific states like **California (CA)** show higher churn volatility compared to the national average.
* **📞 Customer Service:** A high frequency of customer service calls is a strong leading indicator of future churn.

---

## 📂 Repository Structure
```text
├── Data/
│   └── Databel - Data.csv             # Raw Customer Dataset
├── Dashboard/
│   └── Telecom Churn Dashboard.pbix   # Power BI Project File
├── Screenshots/
│   ├── Overview.png                   # Main Dashboard View
│   ├── Demographics.png               # Demographic Deep-dive
│   └── Int_Data_Plane.jpg             # Usage Analysis
└── README.md                          # Project Documentation
