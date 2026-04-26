# 📊 Customer Loyalty & Sales Analytics Dashboard

## 📌 Project Overview

This project presents an interactive **Business Intelligence dashboard** built using **Google Looker Studio**. It analyzes customer behavior, product performance, and geographic sales distribution using real-world sample data.

The dashboard demonstrates how raw data can be transformed into **actionable insights** through:

* Data blending
* Interactive filtering
* Geospatial visualization

---

## 🎯 Business Objective

The goal is to help stakeholders answer:

* **Who** are the key customers?
* **What** products drive revenue?
* **Where** are sales concentrated?

---

## 🛠️ Tools & Technologies

* Google Looker Studio
* Data Blending (Multiple datasets)
* CSV Data (IBM Sample Dataset)

---

## 📂 Dataset

* CustomerLoyaltyProgram.csv
* cust_loyalty_table.csv
* cust_table.csv

---

# 🧭 Dashboard Overview

The dashboard is structured into three key analytical areas:

### 1️⃣ Customer Insights

* Quantity Sold by Gender
* Interactive filters

### 2️⃣ Sales Performance

* Revenue vs Unit Price
* Product-level analysis

### 3️⃣ Geographic Analysis

* Bubble Map
* Heatmap

---

## 🌍 Dashboard Preview

![Dashboard Preview](screenshots/bubble_map_with_slicer.png)

---

## 📊 Key Visualizations

---

### 🌍 Sales Distribution Map by City (Interactive)

![Bubble Map](screenshots/bubble_map_with_slicer.png)

- Bubble size → Quantity Sold  
- Color → Product Line  
- Includes **Order Year slider**  
- Shows global sales distribution  

📌 Insight: High sales concentration in North America and Europe.

---

### 🔥 Sales Intensity Heatmap by Region

![Heatmap](screenshots/heatmap_quantity_sold.png)

- Color intensity represents **sales volume**
- Identifies regional hotspots

📌 Insight: Strong clustering in major metropolitan areas.

---

### 🧱 Sales Intensity Heatmap by Product Line (Time-Filtered)

![Product Heatmap](screenshots/heatmap_productline.png)

- Shows product performance across regions  
- Includes time filtering capability  

📌 Insight: Certain product lines dominate specific regions over time.

---

### 📊 Customer Segmentation by Gender

![Gender Chart](screenshots/quantity_by_gender.png)

- Compares quantity sold across gender  
- Includes dropdown filter  

📌 Insight: Balanced purchasing behavior across genders.

---

### 📈 Revenue vs Unit Price by City

![Revenue Chart](screenshots/revenue_vs_price_city.png)

- Bars → Revenue  
- Line → Unit Sale Price  

📌 Insight: Some cities generate high revenue despite lower unit prices.

---

### 🧱 Product Sales Hierarchy (Treemap)

![Treemap](screenshots/treemap_product_hierarchy.png)

- Hierarchical view: Country → State → City  
- Optional metric: Revenue  

📌 Insight: Reveals dominant regions and product clusters.

---

## ⚙️ Tools & Technologies

- Google Looker Studio  
- Data Blending (Multiple datasets)  
- Interactive Filters & Controls  
- Geographic Visualizations  

---
