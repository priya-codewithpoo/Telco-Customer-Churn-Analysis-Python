# 📊 Telco Customer Churn Analysis — Python Project

## 💡 Project Summary
This Python project analyzes Telco customer churn using Pandas and visualizations. It identifies high-risk customers, operational failures, and retention opportunities to guide data-driven business decisions.

---

## 🔍 Project Overview

This is a **Python-based data analysis project** focused on understanding customer churn in a telecommunications company.
The project demonstrates how Python is used by data analysts for **data cleaning, exploratory data analysis (EDA), visualization, and business insight generation**.

This is a **single-tool project (Python only)** 

---

## 🎯 Business Questions Answered

### 1️⃣ Financial Risk

**Question:** Which customers pose the highest immediate revenue risk if they churn?
**Focus:** Tenure, MonthlyCharges, TotalCharges

### 2️⃣ Operational Failure

**Question:** Which services, contracts, or technical dependencies are causing the most churn?
**Focus:** Contract type, InternetService, TechSupport

### 3️⃣ Retention Opportunity

**Question:** Which customer groups should be targeted to improve long-term retention?
**Focus:** Demographics and service combinations

---

## 🧰 Tools & Libraries Used

* **Python**
* **Pandas, NumPy**
* **Matplotlib, Seaborn**
* **Jupyter Notebook**

---

## 📁 Project Structure

- [1_data_cleaning_and_prep.ipynb](1_data_cleaning_and_prep.ipynb)
- [2_financial_risk_analysis.ipynb](2_analysis_financial_risk.ipynb)
- [3_operational_failure_analysis.ipynb](3_analysis_operational_failure.ipynb)
- [4_retention_opportunity_analysis.ipynb](4_analysis_retention_targets.ipynb)

- [cleaned_telco_data.csv](cleaned_telco_data.csv)

images/
- financial_risk_*.png
- operational_failure_*.png
- retention_opportunity_*.png

---

## 🧹 Data Cleaning & Preparation

* Corrected data types (e.g., `TotalCharges`)
* Handled missing values
* Created tenure-based customer segments
* Exported a cleaned dataset for analysis

---

## 📊 Key Visual Insights

### 📉 Financial Risk Analysis

![Financial Risk](images/financial_risk_churn_by_tenure.png)
![Revenue Risk](images/financial_risk_revenue.png)

### ⚙️ Operational Failure Analysis

![Operational Failure](images/operational_contract_churn.png)
![Tech Support Impact](images/operational_techsupport.png)

### 🎯 Retention Opportunity Analysis

![Retention Opportunity](images/retention_segment_churn.png)

---

## 💡 Key Insights

* Customers with high monthly charges and short tenure present the highest churn risk.
* Month-to-month contracts with Fiber Optic service show the highest churn rates.
* Long-tenure customers without technical support represent strong retention opportunities.

---

## ✅ Why This Project Matters

* Demonstrates real-world Python data analysis workflow
* Focuses on business decision-making
* Portfolio-ready for data analyst roles

---
## 🏁 Conclusion

This project demonstrates a complete Python-based data analysis workflow, transforming raw customer data into clear insights on churn risk, operational issues, and retention opportunities to support data-driven business decisions.


