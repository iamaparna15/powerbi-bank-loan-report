![Power BI](https://img.shields.io/badge/Tool-PowerBI-yellow)
![SQL](https://img.shields.io/badge/Database-SQL-blue)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)

# 📊 Bank Loan Analytics Dashboard (Power BI)

## 🚀 Project Overview

This project presents a comprehensive analysis of a bank's loan portfolio using Power BI. The dashboard enables stakeholders to monitor lending performance, assess risk, and derive actionable insights from loan data.

---

## 💼 Problem Statement

Financial institutions need a clear understanding of loan performance to:

* Identify high-risk (bad) loans
* Monitor repayment and cash flow
* Track lending trends over time
* Optimize decision-making using data

This project addresses these challenges by building an interactive, multi-page dashboard.

---

## 📊 Dashboard Architecture

### 🔹 Dashboard 1: Summary

Provides a high-level overview of loan performance.

**Key KPIs:**

* Total Loan Applications
* Total Funded Amount
* Total Amount Received
* Average Interest Rate
* Average Debt-to-Income Ratio (DTI)

**Additional Analysis:**

* Good vs Bad Loan classification
* Loan Status breakdown (Fully Paid, Current, Charged Off)
* Month-to-Date (MTD) and Month-over-Month (MoM) tracking

---

### 🔹 Dashboard 2: Overview

Focuses on trend and segmentation analysis.

**Visualizations:**

* Monthly Trends (Line Chart)
* State-wise Distribution (Map)
* Loan Term Distribution (Donut Chart)
* Employment Length Analysis (Bar Chart)
* Loan Purpose Breakdown
* Home Ownership Analysis (Tree Map)

**Metrics Used:**

* Total Loan Applications
* Total Funded Amount
* Total Amount Received

---

### 🔹 Dashboard 3: Details

Provides a granular view of loan data.

**Features:**

* Record-level loan data
* Borrower attributes (grade, purpose, home ownership)
* Financial metrics (interest rate, installment)

---

## 🧠 Key Insights

* ~86% of loans are classified as **good loans**, indicating strong portfolio performance
* **Debt consolidation** is the primary reason for borrowing
* Loan applications show a **consistent upward trend across months**
* Higher-risk loans (lower grades) are associated with **higher interest rates**

---

## 🛠️ Technical Implementation

### 🔹 Data Processing

* Data cleaning and transformation using Power Query
* Data modeling with relationships and date tables

### 🔹 SQL (MS SQL Server)

* Data extraction and preprocessing
* Use of:

  * CTEs
  * Aggregations (COUNT, SUM)
  * Date functions (MONTH, DATENAME)

### 🔹 DAX

* KPI calculations
* Time intelligence (MTD, MoM)
* Aggregations using CALCULATE, SUM, SUMX

---

## 📂 Project Structure

* `dashboard.pbix` → Power BI file
* `dataset/` → Source data
* `screenshots/` → Dashboard previews

---

## 📌 How to Use

1. Download the `.pbix` file
2. Open in Power BI Desktop
3. Interact with filters and visuals

---

## 🚀 Future Enhancements

* Predictive modeling for loan default risk
* Real-time data integration
* Deployment via Power BI Service

---

## 👤 Author

Your Name
