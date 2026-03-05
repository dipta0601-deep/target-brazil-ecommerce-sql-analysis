# 📊 Target Brazil E-commerce SQL Analysis (2016–2018)

## 📌 Project Overview
This project analyzes Target’s Brazilian e-commerce operations between 2016 and 2018 using SQL.  

The objective was to extract actionable business insights related to:

- Customer distribution
- Order growth & seasonality
- Revenue & freight movement
- Logistics performance
- Payment behavior & financial risk

This project simulates a real-world Business Analyst / Data Analyst case study.

---

## 🛠️ Tools & Skills Used

- SQL (MySQL)
- Joins (Inner, CTEs)
- Window Functions (LAG, ROW_NUMBER)
- Aggregations (SUM, AVG, COUNT)
- Date & Time Functions
- Business Insight Generation
- Data Cleaning & Validation

---

## 🗂️ Dataset Description

Tables Used:

- customers
- orders
- order_items
- payments
- products
- sellers
- reviews
- geolocation

Analysis was primarily conducted at:
- State level
- Monthly & yearly time level

---

## 🔎 Key Business Problems Solved

### 1️⃣ Order Trend & Seasonality
- Identified year-wise growth trend
- Detected monthly seasonality patterns
- Segmented orders by time of day (Dawn / Morning / Afternoon / Night)

📈 Insight:
Orders showed strong growth with peak demand during May–August.
Majority of purchases were made in Afternoon and Night.

---

### 2️⃣ Market & Customer Distribution
- Analyzed customer concentration across states
- Measured month-on-month order changes using LAG()

📍 Insight:
~40% of customers were concentrated in São Paulo (SP), showing heavy regional dependency.

---

### 3️⃣ Revenue & Economic Impact
- Calculated total order value & freight contribution
- Identified cost growth from 2017 to 2018
- Evaluated payment gap risk

💰 Insight:
Freight cost significantly contributes to order value.
Payment gap was minimal, indicating low financial risk.

---

### 4️⃣ Logistics & Delivery Efficiency
- Measured actual vs estimated delivery time
- Ranked states by delivery speed
- Identified states with fastest deliveries

🚚 Insight:
Average delivery delay was only ~0.1 days — high operational efficiency.

---

### 5️⃣ Payment Behavior Analysis
- Month-on-month trend by payment type
- Installment usage analysis

💳 Insight:
Installment-based payments were widely used.
Payment system is stable and low risk.

---

## 📊 Business Recommendations

- Reduce dependency on São Paulo market
- Invest in regional warehouses to optimize freight cost
- Align inventory with seasonal demand
- Design time-based marketing campaigns

---

## 🎯 What This Project Demonstrates

✔ Ability to translate business problems into SQL queries  
✔ Strong understanding of aggregations & window functions  
✔ Practical experience in trend analysis  
✔ Capability to derive business recommendations from raw data  
✔ Entry-level Data Analyst skillset  

---

## 👨‍💻 Author

**Diptadeep Ata**  
Aspiring Data Analyst  
SQL | Data Analysis | Business Intelligence  

---