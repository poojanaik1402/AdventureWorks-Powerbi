# 📊 AdventureWorks Power BI Dashboard

This Power BI project is a complete end-to-end business intelligence solution built using the **AdventureWorks dataset**. The dashboard demonstrates how raw transactional and reference data can be cleaned, modeled, and visualized to provide actionable business insights.

The main goal of this project is to provide a high-level and detailed overview of **sales performance**, **customer demographics**, **product trends**, and **regional insights** using the AdventureWorks dataset. This dashboard can assist executive teams, product managers, and sales analysts in making data-driven decisions.

---

### 📊 Dataset Description

The dataset is based on **AdventureWorks**, a fictional bicycle and accessories manufacturing company. It contains historical sales and product data from multiple business units.

Included Tables:
- Calendar Lookup
- Customer Lookup
- Product Categories & Subcategories
- Product Lookup
- Sales Data (Fact)
- Territory Lookup

---

### 🧹 Data Preparation

Data transformation and preparation were done using **Power Query**. Key steps included:

- Renaming and restructuring columns
- Removing null or irrelevant fields
- Filtering unused records (e.g., blank customers)
- Creating custom calculated columns (e.g., Profit = Revenue - Cost)
- Converting data types and adding friendly column names

---

### 🔗 Data Model

The data model was built in a **star schema**, connecting fact and dimension tables via one-to-many relationships.

Key Relationships:
- Sales → Customer
- Sales → Product
- Product → Subcategory → Category
- Sales → Territory
- Sales → Calendar

---

### 🧮 DAX Measures

Custom DAX measures were written to calculate dynamic KPIs across time, geography, product, and customer segments.

Sample Measures:
- Total Sales
- Total Profit
- Total Orders
- Customer Count
- Profit Margin
- YTD, MTD, QTD Sales using TOTALYTD, DATESYTD, CALCULATE, etc.

---

### 📈 Dashboard Views

#### 🧭 Executive Dashboard  
Provides a high-level summary of key performance indicators including total sales, profit, number of orders, customer count, and overall trend. Ideal for stakeholders to get a quick overview of business performance.  
![Executive Dashboard](https://raw.githubusercontent.com/poojanaik1402/AdventureWorks-Powerbi/main/Content/Executive_dashboard.png)

---

#### 🗺️ Map View  
Displays geographic distribution of sales and customers by region and territory. Useful for identifying top-performing regions and analyzing regional market trends.  
![Map View](https://raw.githubusercontent.com/poojanaik1402/AdventureWorks-Powerbi/main/Content/Map%20View.png)

---

#### 📦 Product Details  
Drills down into product-level performance including sales by category and subcategory, most sold products, and contribution to total revenue. Helps in identifying high and low-performing products.  
![Product Details](https://raw.githubusercontent.com/poojanaik1402/AdventureWorks-Powerbi/main/Content/Product_details.png)

---

#### 👥 Customer Details  
Analyzes customer behavior and segmentation, including top customers by revenue, frequency of purchases, and region-wise customer trends.  
![Customer Details](https://raw.githubusercontent.com/poojanaik1402/AdventureWorks-Powerbi/main/Content/Customer_details.png)

---

### 📌 Visualizations Used

- KPI Cards  
- Clustered Column Charts  
- Pie Charts  
- Maps  
- Matrix Tables  
- Slicers for Year, Region, Category, and more  

---

### 🛠 Technologies Used

- Power BI Desktop  
- Power Query (M Language)  
- DAX (Data Analysis Expressions)  
- AdventureWorks Sample Dataset  
- Data Modeling (Star Schema)  

---

### 📌 License
This project is intended for **educational and portfolio use only**. Do not use for commercial purposes.
