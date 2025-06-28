# 📊 Amazon Brazil E-commerce Data Analysis (SQL Project)

> Advanced Data-Driven Analysis Using SQL  
> **By Ansh Jain | NextLeap Data Analyst Fellow | June 2025**

---

## 📌 Project Objective

To analyze Amazon Brazil’s real-world e-commerce data using **Advanced SQL** techniques and generate **actionable insights** that can help Amazon India optimize its market entry, customer segmentation, product pricing, and operational strategies.

---

## 🧠 Key Insights Derived

- 📦 Product-level pricing strategy and price consistency insights
- 💳 Customer preferences in payment methods across value segments
- 📈 Seasonal trends, top-performing categories & customer types
- 🧍‍♂️ Advanced customer segmentation using recursive CTEs and window functions
- 🛍️ Identification of top-selling products and high-value buyers

---

## 🗂️ Files in This Repository

| File Name | Description |
|-----------|-------------|
| `Advanced Data Analysis using SQL By Ansh Jain.docx` | Detailed project report with problem statements, query breakdowns, visual outputs, and business recommendations |

| `Amazon Analysis.sql` | All 19 advanced SQL queries, including joins, window functions, CTEs, recursive queries, and segmentation |

| `schema.png` | Entity-Relationship diagram showing the 6-table relational schema of the Amazon Brazil dataset |

---

## 🔍 Dataset Overview

Source: Next Leap 

**Tables Used:**
- `customers`: Geolocation, demographics
- `orders`: Purchase and delivery timelines
- `order_items`: Item-level details including price, quantity
- `products`: Product categories and descriptions
- `sellers`: Seller data and fulfillment partners
- `payments`: Payment types, values, and methods

---

## 🛠️ Tools & Technologies

- SQL (PostgreSQL syntax)
- pgAdmin / DBeaver (execution)
- Excel (for exports and visualizations)
- Git & GitHub (project versioning)

---

## 📊 SQL Techniques Used

- Advanced Joins (INNER, LEFT)
- Aggregation functions (AVG, SUM, COUNT, STDDEV)
- Common Table Expressions (CTEs)
- Recursive CTEs for cumulative and monthly sales
- Window Functions (`RANK`, `DENSE_RANK`, `LAG`)
- CASE statements for segmentation
- Temporal operations for seasonality & trends

---

## 📈 Business Questions Answered (19 in total)

### 🔹 Analysis I – Payment, Pricing & Product Insights
1. Standardizing payment values
2. Distribution of payment types
3. Identifying smart products within a price range
4. Top 3 months by total sales
5. Categories with high price variation
6. Most consistent payment methods
7. Products with incomplete or invalid category names

### 🔹 Analysis II – Customer Behavior & Revenue Patterns
8. Payment type preference across spending segments
9. Category-wise pricing statistics
10. Identifying repeat customers
11. Customer lifecycle segmentation (New, Returning, Loyal)
12. Top revenue-generating product categories

### 🔹 Analysis III – Time Series & Advanced Segmentation
13. Seasonal comparison of total sales
14. Identifying above-average sales volume products
15. Monthly revenue trends for 2018
16. CTE-based customer segmentation (Occasional, Regular, Loyal)
17. Top 20 high-value customers by revenue
18. Monthly cumulative sales using recursive CTE
19. Month-over-month growth rate calculation

---

## 🧾 Sample Business Recommendation

> 📌 *“Credit cards show the highest transaction value (165 BRL); hence Amazon India should prioritize partnerships with top Indian credit card issuers, offering EMI and cashback options during festive sales.”*

Every question in the report is followed by business use cases and detailed recommendations tailored to Amazon India's e-commerce strategy.

---

## 🔗 Live Project URL

👉 [**GitHub Repository Link**](https://github.com/anshjain1409/amazon-brazil-sql-analysis)  
(Replace with your actual GitHub link when uploading)

---

## 📣 Author

**Ansh Jain**  
Fellow at [NextLeap Data Analyst Fellowship](https://www.nextleap.app/)  
📧 anshjain14092004@gmail.com  
📍 India


