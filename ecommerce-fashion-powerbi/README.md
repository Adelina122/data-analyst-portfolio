# E-Commerce Sales & Customer Analysis (Power BI)

## 📌 Project Overview
This project presents an end-to-end **Power BI analytics dashboard** built on an e-commerce dataset.  
The goal was to transform raw transactional and customer data into **business-ready insights** focusing on:

- Sales performance (Q2)
- Profitability & discount impact
- Customer behavior & value segmentation

The report is designed for **business stakeholders** and follows best practices in data modeling, DAX measures, and dashboard design.

---

## 🧱 Data Model
The dataset follows a **star schema** structure:

- **Fact Table**
  - `sales` (merged transactional data)

- **Dimension Tables**
  - `customers`
  - `products`
  - `calendar`

A dedicated **Calendar table** was created to support time intelligence and consistent filtering across visuals.

---

## 📊 Report Pages

### 1️⃣ Sales Overview (Q2)
Key focus:
- Revenue, Profit, Margin, Orders
- Monthly revenue & profit trend
- Revenue by country, category, and channel

Purpose:
> Understand overall sales performance and geographic/channel distribution.

---

### 2️⃣ Profitability Analysis
Key focus:
- Discounted vs non-discounted revenue
- Profit by marketing campaign
- Quantity vs revenue relationship
- Top & Bottom 5 products by revenue

Purpose:
> Identify profit drivers, discount impact, and underperforming products.

---

### 3️⃣ Customer Analysis
Key focus:
- Total customers and purchasing behavior
- Customer value segmentation
- Customers by age range and country
- Average revenue per customer trend

Purpose:
> Understand **who the customers are** and **how valuable they are**.

---

## 🧮 Key Measures (DAX)
- Total Revenue
- Total Profit
- Profit Margin %
- Total Orders
- Total Customers
- Avg Revenue per Customer
- Avg Orders per Customer
- Customer Value Segmentation
- Discounted Revenue
- Repeat Customers

---

## 🛠 Tools & Technologies
- Power BI
- DAX
- Power Query
- GitHub (documentation & version control)

---


## 📂 Repository Contents
- Power BI report file (`.pbix`)
- Screenshots of report pages
- `README.md`
- `insights.md`
