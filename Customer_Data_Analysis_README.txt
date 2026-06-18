# 📊 Customer Data Analysis Dashboard | Power BI

## 📌 Project Overview

The **Customer Data Analysis Dashboard** is an end-to-end Power BI project designed to analyze customer purchasing behavior across multiple shopping malls in Istanbul from 2021–2023. The dashboard transforms raw transactional data into actionable business insights through interactive visualizations and advanced DAX calculations.

The project focuses on identifying revenue drivers, customer demographics, product performance, payment trends, and mall-wise business performance to support data-driven decision-making.

---

## 🎯 Business Objectives

* Analyze overall sales and revenue performance.
* Understand customer demographics and purchasing patterns.
* Identify top-performing product categories.
* Evaluate payment method preferences.
* Compare shopping mall performance.
* Generate actionable recommendations for business growth.

---

## 🛠️ Tools & Technologies

| Tool        | Purpose                                    |
| ----------- | ------------------------------------------ |
| Power BI    | Data Visualization & Dashboard Development |
| Power Query | Data Cleaning & Transformation             |
| DAX         | KPI & Measure Creation                     |
| Excel / CSV | Data Source                                |

---

## 📂 Dashboard Structure

### 1️⃣ Executive Overview

Provides a high-level summary of business performance.

**KPIs**

* Total Revenue
* Total Transactions
* Total Customers
* Units Sold
* Average Order Value

**Visuals**

* Revenue Trend
* Revenue by Gender
* Revenue by Category
* Payment Method Distribution

---

### 2️⃣ Sales Analysis

Analyzes sales performance over time.

**Key Metrics**

* MTD Revenue
* QTD Revenue
* YTD Revenue
* YoY Growth %

**Visuals**

* Monthly Revenue Trend
* Quarterly Performance
* Category Revenue Analysis

---

### 3️⃣ Customer Analysis

Examines customer demographics and spending behavior.

**Insights**

* Gender-wise Revenue
* Age Group Distribution
* Customer Spending Patterns
* Average Spend per Customer

---

### 4️⃣ Product Analysis

Evaluates category-level performance.

**Key Insights**

* Top Revenue Categories
* Units Sold by Category
* Average Order Value
* Revenue Contribution Analysis

**Top Categories**

1. Clothing
2. Shoes
3. Technology

---

### 5️⃣ Mall Performance Analysis

Compares performance across shopping malls.

**Insights**

* Revenue by Mall
* Transactions by Mall
* Gender-wise Revenue Distribution
* Top & Bottom Performing Malls

---

## 📈 Key Business Insights

### 👩 Customer Insights

* Female customers contribute approximately **60% of total revenue**.
* The **35–44 age group** generates the highest overall revenue.
* Customers aged **55–64** have the highest average spending per transaction.

### 🛍 Product Insights

* **Clothing** contributes over **45% of total revenue**.
* **Technology** has the highest average order value.
* Clothing, Shoes, and Technology account for more than **94% of total revenue**.

### 💳 Payment Insights

* Cash remains the most preferred payment method.
* Payment preferences show minimal variation across genders.

### 🏬 Mall Insights

* The top three malls generate more than half of the total revenue.
* Revenue is highly concentrated among a small number of locations.

---

## 📊 Sample DAX Measures

```DAX
Total Revenue =
SUMX(
    customer_data_analysis,
    customer_data_analysis[Quantity] *
    customer_data_analysis[Price]
)

Total Customers =
DISTINCTCOUNT(customer_data_analysis[Customer ID])

Total Transactions =
DISTINCTCOUNT(customer_data_analysis[Invoice No])

Units Sold =
SUM(customer_data_analysis[Quantity])

Average Order Value =
DIVIDE([Total Revenue], [Total Transactions])
```

---

## 💡 Recommendations

* Strengthen marketing campaigns targeting female customers.
* Increase cross-selling opportunities between Clothing and Technology categories.
* Improve performance of lower-performing malls through localized promotions.
* Encourage digital payments through customer incentives.
* Develop loyalty programs for high-value customer segments.

---

## 📷 Dashboard Preview

### Dashboard Pages

* Executive Overview
* Sales Analysis
* Customer Analysis
* Product Analysis
* Mall Analysis

> Add dashboard screenshots here for better project presentation.

---

## 🚀 Skills Demonstrated

* Data Cleaning & Transformation
* Data Modeling
* DAX Calculations
* Business Intelligence
* Dashboard Design
* Data Storytelling
* KPI Development
* Analytical Thinking

---

## 👨‍💻 Author

**Prathmesh Waykar**

LinkedIn: https://www.linkedin.com/in/prathmesh-waykar-86954b276/

GitHub: https://github.com/prathmeshwaykar

---

## ⭐ If you found this project useful, please consider giving it a star!
