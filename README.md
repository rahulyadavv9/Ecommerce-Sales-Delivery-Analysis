📊 E-Commerce Sales & Delivery Performance Analysis

🧠 Business Problem 

An e-commerce company was experiencing steady growth in orders and revenue, but leadership noticed a worrying pattern — **customer satisfaction was inconsistent, delivery delays were frequent, and a significant number of orders were being cancelled or marked unavailable**.

At first glance, revenue looked healthy. But underneath the surface:

* Customers were receiving orders late
* Reviews were declining
* Logistics costs were rising in certain regions
* A large portion of revenue depended on a few states and payment methods

The company needed answers to critical questions:

* Are delivery delays affecting customer satisfaction?
* Which regions are operationally inefficient?
* How many orders are being lost and why?
* Is the business overly dependent on specific segments?

To solve this, i have built a data-driven dashboard to uncover hidden inefficiencies and provide actionable insights.

---

🎯 Project Objective

To analyze sales, delivery performance, and customer experience using structured data and transform it into a business intelligence dashboard that helps stakeholders:

* Monitor key KPIs
* Identify operational bottlenecks
* Understand customer behavior
* Improve decision-making

---

 🧱 Data Modeling & Preparation

 🔹 Data Cleaning (SQL)

* Removed duplicates and inconsistencies
* Standardized formats (dates, categories, payments)
* Handled missing/null values

---

 🔹 Fact Table Created

* `fact_orders_final`

---

 🔹 Dimension Tables

* `dim_customers`
* `dim_products_final`
* `dim_reviews_final`

---

 🔹 Transformations

* Aggregated payments at order level
* Ensured proper joins between datasets
* Built a star schema model

---

 📊 Power BI Implementation

 🔹 Data Model

* Star schema with fact and dimension tables
* Relationships optimized for performance
* Date table created for time intelligence

---

 📈 Key Metrics (DAX Measures)

* Total Revenue
* Total Orders
* Total Customers
* Average Order Value
* Revenue per Customer
* On-Time Delivery %
* Average Delivery Days
* Cancellation %
* Low Rating %

---

 📅 Time Intelligence

* Previous Month Sales
* Month-over-Month Growth %

---

 🎨 Dashboard Pages

---

 🟦 Page 1: Sales Performance

 📌 Key Highlights:

* Revenue trends over time
* Top performing product categories
* Revenue by state
* Payment method analysis

 🔍 Insights:

* Revenue declined by 7% MoM
* Top state contributes 37% of total revenue
* Heavy dependency on credit cards (87%)

---

 🟩 Page 2: Delivery & Customer Experience

 📌 KPIs:

* Avg Delivery Days → 12 days
* On-Time Delivery → 92.1%
* Bad Reviews → 14.63%
* Cancelled Orders → 625
* Unavailable Orders → 609

---

 📊 Visuals:

 📈 Delivery Trend

* Delivery improved from 15 → 9 days over time

 📦 Delivery Buckets

* Majority deliveries fall into Delayed category
* Very few fast deliveries

 📍 State Analysis (Scatter Plot)

* High freight cost → higher delivery time
* Remote states show inefficiency

---

 🔍 Key Insights

* 🚚 Delivery performance improved but still inconsistent
* 🌍 Certain states show **logistics inefficiencies**
* ⭐ Poor ratings strongly correlate with delayed delivery
* ❌ Over **1,200+ lost orders** (cancelled + unavailable)
* 💳 Heavy dependency on a single payment method
* 📦 Majority deliveries are **not fast → operational gap**

---

 🧠 Business Recommendations

* Improve last-mile delivery in high-delay regions
* Optimize logistics cost vs delivery time trade-off
* Reduce dependency on one payment method
* Focus on reducing cancellations and unavailable orders
* Enhance delivery speed to improve customer satisfaction


---

 🚀 Project Outcome

This dashboard provides:

* A 360° view of business performance
* Clear visibility into operational inefficiencies
* Actionable insights to improve delivery and customer experience

---
📸 Overall Report: https://github.com/rahulyadavv9/Airbnb-Performance-/blob/main/Airbnb%20dashboard..pdf

Main Page https://github.com/rahulworkedit-cell/Airbnb-Performance-/blob/main/Airbnb%20Dashboard%201.png

Dashboard 2:(Overall Ratings) https://github.com/rahulworkedit-cell/Airbnb-Performance-/blob/main/Airbnb%20Dashboard%202.png

Dashboard 2:(Detailled Ratings) https://github.com/rahulyadavv9/Airbnb-Performance-/blob/main/Airbnb%20ratings%20detailed.png
---

 📌 Conclusion

What initially looked like a healthy business revealed:

👉 Hidden inefficiencies in logistics
👉 Customer dissatisfaction signals
👉 Revenue risks due to dependencies

This project demonstrates how data analysis can uncover deeper truths behind surface-level metrics and drive better business decisions.

---
