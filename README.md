# 🏦 Comprehensive Banking Risk Insights

![Power BI Dashboard](https://github.com/bhaskarpal1707/bhaskarpal1707-Banking-Risk-Insights-Project/blob/main/Banking%20Dashboard%20Image.png?raw=true)

## 📘 Overview

This end-to-end project focuses on understanding **risk analytics** in the **banking and financial services domain**—how financial institutions can use data to make smarter lending decisions and avoid losing money.

The core goal?  
> Build a basic understanding of how banks assess lending risks and use historical customer data to **predict loan repayment behavior**.

By transforming raw data into a fully interactive **Power BI dashboard**, this project provides a powerful lens through which stakeholders can explore client behavior, banking activity, and risk patterns.

---

## 🧩 Problem Statement

> How can data help minimize the risk of losing money when lending to customers?

---

## 💡 Solution Approach

Our solution leverages modern **data analytics** and **interactive dashboards** to guide decision-making. Using Power BI, the system helps banks:

- Approve loans only if the applicant is likely to repay.
- Reject or reassess risky profiles.
- Use visual insights to make fast, data-backed financial decisions.

---

## 🗂 Dataset & Tables

The dataset, originally in Excel, was cleaned and explored in Python. It includes multiple interrelated tables:

- **Banking Relationship**
- **Client-Banking**
- **Gender**
- **Investment Advisor**
- **Period**

Each table is linked using primary and foreign keys, enabling rich, joined analysis across client demographics and financial behavior.

---

## 🔧 Workflow Breakdown

### 1. Data Preparation
- 📂 Original format: Excel workbook (`.xlsx`)
- 🔄 Converted to: CSV files
- 🧩 Loaded into: **MySQL** database

### 2. Database Integration
- Connected **MySQL to Python** via `mysql-connector`
- Pulled datasets from SQL for exploration and cleaning

### 3. Data Cleaning & Preprocessing (Python)
- Null handling, type casting, formatting
- Data sanity checks and validation

### 4. Exploratory Data Analysis (EDA)
Performed in Jupyter Notebook using Pandas, Matplotlib, and Seaborn.

![Image 1](https://github.com/bhaskarpal1707/bhaskarpal1707-Banking-Risk-Insights-Project/blob/main/Image%201.jpg?raw=true)

#### EDA Breakdown:
- **Bivariate Analysis**
- **Univariate Analysis**
- **Numerical Summary**
- **Heatmaps**

### 🧠 Key Insights:

- **Deposits and Savings Behavior**  
  Strong correlation between `Bank Deposits` and `Saving Accounts` suggests that customers with active deposits often maintain high savings balances.

- **Income, Age, and Accumulation**  
  Higher `Estimated Income` and `Age` correlate with greater balances across Superannuation, Checking, and Savings—indicating typical financial lifecycle trends.

- **Low Correlation with Properties Owned**  
  Property ownership appeared relatively independent from banking variables, likely influenced by external factors.

- **Business vs. Personal Banking**  
  Business Lending and Personal Loans show moderate linkage, suggesting some customers hold both types of liabilities, but generally serve distinct customer segments.

---

## 📊 Power BI Dashboard

The final deliverable is a set of **four interconnected dashboards** built in Power BI, enabling rich visual exploration of banking risk insights.

![Image 2](https://github.com/bhaskarpal1707/bhaskarpal1707-Banking-Risk-Insights-Project/blob/main/Image%202.jpg?raw=true)

### 🔹 1. Home Dashboard
- Offers a **high-level snapshot** of the bank’s operations and client metrics.
- Includes filters to slice the data by **nationality**, **advisor**, **bank**, and **client type**.
- Visual summaries highlight key indicators like total loan amount, number of clients, and overall account balances.

### 🔹 2. Loan Analysis Dashboard
- Focused exclusively on **loan-related insights**.
- Tracks metrics like:
  - Total number and value of approved loans
  - Loan distribution by **client type**, **gender**, and **nationality**
  - Loan-to-income ratios and high-risk loan segments
- Helps determine **which profiles are most likely to repay** and which are risk-prone.

### 🔹 3. Deposit Analysis Dashboard
- Visualizes trends in customer **savings and deposit behavior**.
- Highlights:
  - Correlation between **bank deposits** and **saving accounts**
  - Deposit patterns across **income groups**, **age brackets**, and **advisors**
  - Which account types attract the most investor activity

### 🔹 4. Summary Dashboard
- A compact **executive-level overview**.
- Consolidates critical KPIs from the other dashboards into a **single screen**.
- Great for presenting to stakeholders, giving a holistic view of:
  - Risk exposure
  - Client distribution
  - Lending effectiveness

---

## 🏁 Conclusion

This project demonstrates how powerful insights can be uncovered from raw banking data using modern tools like **Python, SQL**, and **Power BI**. Financial institutions can now:

- Reduce lending risk
- Identify trustworthy applicants
- Improve operational efficiency using automated analytics

---

## 🚀 Future Scope

Here are some ways this project can evolve further:

- 🔍 **Investor-Level Drilldowns**  
  Track total loan amounts and liabilities per individual investor.

- 🧭 **Competitive Benchmarking**  
  Understand why private banks attract more clients—and let public banks adapt strategies accordingly.

- 🌍 **Geographic & Demographic Insights**  
  Analyze loan trends by nationality to identify high-risk or high-value customer segments.

- 🏦 **Account Type Breakdown**  
  Visualize how funds are distributed across Checking, Savings, Business Loans, and more.

---

## 📁 Project Files

- `Banking.xlsx` – Original Excel dataset
- `Banking.csv` – Transformed version for SQL
- `Banking - EDA Case Study.ipynb` – Python notebook for EDA
- `Banking Insights Dashboard.pbix` – Power BI dashboard file
- `Banking Risk Insights End to End Project Video.mp4` – Demo walkthrough

---

## 📽️ Demo Video

> *Watch the full project in action with live dashboard walkthrough and insights explanation.*

🎬 [Click here to view demo](https://github.com/bhaskarpal1707/bhaskarpal1707-Banking-Risk-Insights-Project/blob/main/Banking%20Risk%20Insights%20End%20to%20End%20Project%20Video%20(1).mp4)

---

Feel free to fork, use, or contribute to improve this project further!

---
**Author**: Bhaskar Pal
```
📧 Contact: [bhaskarpal.official@gmail.com 
```

