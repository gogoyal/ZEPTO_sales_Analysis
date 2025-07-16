# 📊 Zepto Data Analysis using PostgreSQL

This project involves detailed data analysis on Zepto's operational and customer data using **PostgreSQL**. The goal was to derive meaningful insights about customer behavior, order patterns, delivery efficiency, and product performance to aid strategic business decisions.

---

## 📚 About the Dataset

This project explores the [Zepto Inventory Dataset on Kaggle](https://www.kaggle.com/datasets/palvinder2006/zepto-inventory-dataset/data?select=zepto_v2.csv), which contains information on over **3,000+ SKUs** across categories like **Fruits & Vegetables, Dairy, Packaged Foods, Beverages**, and more. Zepto, a fast-growing 10-minute grocery delivery platform, provides a rich dataset for inventory and retail pricing analysis.

**The dataset supports various analytical objectives such as:**

- 📉 **Discount trends by category**  
  Understand how discounts are distributed across different product categories and price points.

- 🛒 **Inventory availability and stock-outs**  
  Identify frequently out-of-stock products and analyze stock trends.

- 💸 **Price distribution and pricing strategy**  
  Analyze the spread of pricing across brands and SKUs to infer the pricing model.

- 🧾 **Product naming patterns**  
  Suitable for NLP tasks like word cloud generation and naming trend analysis.

---

## 🚀 Project Highlights

- ✅ Cleaned and structured raw Zepto data.
- 📌 Performed exploratory data analysis (EDA) using SQL queries.
- 📦 Analyzed customer ordering trends, delivery times, and item popularity.
- 📍 Extracted location-wise performance of the Zepto delivery service.
- 📈 Built SQL views for ongoing reporting and analysis.
- 📊 Derived KPIs such as:
  - Average delivery time
  - Repeat customer rate
  - Most frequently ordered items
  - Revenue per location

---

## 🛠️ Tech Stack

- **Database**: PostgreSQL  
- **Tools Used**: pgAdmin / DBeaver / SQL Shell  
- **Languages**: SQL  

---

## 🔍 Key SQL Concepts Used

- `GROUP BY`, `ORDER BY`, `HAVING`, `JOINs`
- Window functions (`ROW_NUMBER()`, `RANK()`)
- CTEs (Common Table Expressions)
- Subqueries
- Views and Indexing for performance optimization

---

## 📈 Sample Insights

- 🔄 **Repeat Order Rate**: 64% of customers placed more than one order in a month.
- 🕐 **Fastest Delivery Location**: South Mumbai had the fastest average delivery time of 8.2 minutes.
- 🌟 **Top-selling Item**: Full cream milk was the most ordered item across all zones.

---

## 🧠 What I Learned

- Writing complex analytical SQL queries.
- Structuring large-scale transactional data for analysis.
- Using PostgreSQL performance tips like indexing and materialized views.
- Translating business questions into database queries.

---

## 💡 How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/gogoyal/ZEPTO_sales_Analysis.git


