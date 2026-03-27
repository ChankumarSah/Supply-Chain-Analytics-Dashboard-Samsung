# 📦 Supply Chain Analytics Dashboard – Samsung (Power BI)

## 📊 Project Overview

This project presents an **interactive Power BI dashboard analyzing Samsung’s supply chain operations**.

The dashboard provides insights into **revenue, profit, inventory levels, shipment performance, supplier efficiency, and customer demand patterns**.

It demonstrates an **end-to-end data analytics workflow**, including **data modeling, transformation, and visualization using Power BI and DAX**.

---

# 🎯 Business Objective

In a large-scale supply chain like Samsung’s, businesses need to answer critical questions such as:

* Which **products generate the highest revenue?**
* How efficiently is **inventory being managed?**
* Which **suppliers have the best lead time performance?**
* How do **shipment delays impact business operations?**
* Which **channels contribute the most to total sales?**

This dashboard enables stakeholders to make **data-driven decisions** for optimizing operations and profitability.

---

# 🛠 Tools & Technologies Used

* **Power BI** – Dashboard development and visualization  
* **DAX** – Calculated measures and KPIs  
* **SQL** – Data querying and transformation  
* **Excel / CSV** – Data source  
* **Data Modeling** – Star schema implementation  

---

# 📂 Dataset Description

The dataset is structured using a **Star Schema**, consisting of:

### 🔹 Dimension Tables
* `dim_customer` – Customer details  
* `dim_product` – Product information  
* `dim_supplier` – Supplier details  
* `dim_facility` – Warehouse / facility data  
* `dim_date` – Date hierarchy  

### 🔹 Fact Tables
* `fact_sales` – Sales transactions  
* `fact_inventory` – Inventory levels  
* `fact_shipment` – Shipment details  
* `fact_procurement` – Procurement data  
* `fact_production` – Production records  

This structure enables efficient and scalable analysis of supply chain data.

---

# 🔄 Data Processing Workflow

The project follows a structured analytics workflow:

1. Data collection from multiple CSV sources  
2. Data cleaning and preprocessing  
3. Data modeling using **Star Schema**  
4. Importing data into Power BI  
5. Creating relationships between tables  
6. Building calculated measures using **DAX**  
7. Designing an interactive dashboard  

---

# 📊 Dashboard Features

## 📈 KPI Overview

The dashboard includes key performance indicators such as:

* **Total Revenue:** 93.06M  
* **Total Sales:** 88.20M  
* **Total Profit:** 24.28M  
* **Profit Margin:** 27.53%  
* **Total Shipments:** 3916  

These KPIs provide a quick overview of overall business performance.

---

## 🏭 Supplier Performance Analysis

* Evaluates supplier efficiency based on **lead time**
* Identifies suppliers with the **fastest delivery performance**
* Helps optimize procurement decisions  

---

## 📦 Inventory Analysis

* Tracks **inventory levels by product**
* Identifies products with **high stock accumulation**
* Supports inventory optimization strategies  

---

## 📊 Revenue & Profit Trends

* Monthly analysis of **revenue and profit trends**
* Identifies **peak business periods**
* Helps in forecasting and planning  

---

## 🚚 Shipment & Delay Analysis

* Analyzes shipment performance across carriers  
* Identifies **delayed shipments impacting revenue**  
* Helps improve logistics efficiency  

---

## 🛒 Sales Channel Analysis

* Compares sales across platforms like:
  * Amazon  
  * Flipkart  
  * Best Buy  
* Identifies top-performing sales channels  

---

# 📊 Key Insights

* 📅 **October recorded the highest revenue (~10.4M)** indicating strong seasonal demand  
* 📈 Revenue shows a **steady upward trend in the last quarter**, highlighting business growth  
* 🛒 **Amazon leads in total sales performance**, contributing the highest revenue share  
* 🛍️ Sales are **highly concentrated on a few platforms**, indicating dependency on major channels  
* 📦 **Galaxy Buds has the highest inventory stock**, suggesting potential overstocking  
* 📦 Some products have **high inventory but low sales**, indicating demand-supply mismatch  
* 📊 Inventory distribution is **uneven across products**, highlighting the need for better stock planning  
* 🚚 **Shipment delays significantly affect delivery performance**, especially with certain carriers  
* 🚚 A few carriers contribute disproportionately to **shipment delays**, requiring optimization  
* 🏭 **Supplier lead time plays a key role in operational efficiency**  
* 🏭 Suppliers with shorter lead times show **better reliability and performance**  
* 📉 Some months show **profit dips despite high revenue**, indicating higher operational costs  
* 💰 High revenue products do not always generate **high profit margins**, suggesting cost inefficiencies  
* 📅 Seasonal patterns indicate **demand spikes in specific months**, useful for forecasting  
* 📦 Efficient inventory management can **reduce holding costs and improve cash flow**
---

# 📷 Dashboard Preview

![Supply Chain Dashboard](supply_chain_analytics_dashboard_samsung.png)

---

# 🚀 How to Use This Project

1. Download or clone the repository  
2. Open the `.pbix` file in **Power BI Desktop**  
3. Load dataset if required  
4. Explore the interactive dashboard using filters  

---

# 💡 Skills Demonstrated

* Data Modeling (Star Schema)  
* Power BI Dashboard Development  
* DAX Calculations  
* Business Intelligence Analysis  
* Data Visualization  
* Supply Chain Analytics  

---

# 👨‍💻 Author

**Chandan Kumar Sah**  

**Data Analyst | Business Intelligence Enthusiast**  

GitHub:  
https://github.com/ChankumarSah  

---

⭐ If you found this project useful, consider giving it a **star**.
