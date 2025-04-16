---

# **Amazon E-Commerce Analytics – Live Tableau Dashboard**

---

This Project simulates a real-world e-commerce analytics project for an Amazon-like online retail platform. It covers **end-to-end data handling**, from database schema design and advanced SQL queries to **real-time dashboarding in Tableau** using a **live SQL Server connection**.

---

## Project Overview

- Designed and implemented a **relational database schema** with 9 interconnected tables (orders, products, customers, inventory, payments, shipping, etc.)
- Cleaned and imported synthetic data using SQL Server Management Studio (SSMS)
- Wrote **20+ advanced SQL queries** to solve real-world business questions 
- Connected SQL Server to Tableau using **Live Connection** (no extract)
- Built fully interactive dashboards and KPIs to reflect **real-time updates** in the database

---
**Data Source Model (ER View)**
![ERD Scratch](https://github.com/Priyanka504595/Amazon_Analytics_Advanced_SQL_Project/blob/master/ERD_image.jpg)
The Tableau data model is built on a well-defined star schema using a live connection to a Microsoft SQL Server database. At the core is the orders fact table, which connects to dimension tables such as customers, sellers, payments, shipping, order_items, and products. Further dimensional context is provided through category and inventory tables. These relationships enable dynamic, real-time insights into customer behavior, sales performance, inventory status, and operational efficiency. This structure ensures scalability, efficient querying, and seamless integration across Tableau visualizations for e-commerce analytics.
---
![ERD Scratch](https://github.com/Priyanka504595/Amazon_Analytics_Advanced_SQL_Project/blob/master/ERD_image.jpg)
**Top 10 Products by Sales**
This horizontal bar chart highlights the top 10 products ranked by total sales revenue, providing a quick view of bestsellers. The deep red color intensity reflects higher sales, helping stakeholders instantly identify the most profitable products. This visualization supports inventory prioritization, pricing strategy, and marketing focus areas.
---
![ERD Scratch](https://github.com/Priyanka504595/Amazon_Analytics_Advanced_SQL_Project/blob/master/ERD_image.jpg)
**Revenue by Category**
This pie chart visualizes the revenue contribution of each product category. The dominance of the electronics category is clearly visible, occupying nearly 90% of total sales. This helps in understanding category performance and market focus, allowing businesses to evaluate diversification or expand underperforming segments.
---
![ERD Scratch](https://github.com/Priyanka504595/Amazon_Analytics_Advanced_SQL_Project/blob/master/ERD_image.jpg)
**Monthly Sales Trends (Last 4 Years)**
This line chart shows the fluctuation of total monthly sales over the past four years. Spikes and dips are easily visible, making it useful for identifying seasonal trends, promotional impacts, or potential issues such as supply chain disruption. It serves as a backbone for demand forecasting and revenue planning.
---
![ERD Scratch](https://github.com/Priyanka504595/Amazon_Analytics_Advanced_SQL_Project/blob/master/ERD_image.jpg)
**Inventory Stock Alerts**
This horizontal bar chart presents low-stock products where inventory levels are under a critical threshold (e.g., less than 10 units). Products are sorted by stock left, with color intensity representing urgency. This visualization is essential for warehouse and procurement teams to trigger timely restocks and avoid stockouts.
---
![ERD Scratch](https://github.com/Priyanka504595/Amazon_Analytics_Advanced_SQL_Project/blob/master/ERD_image.jpg)
**Top Performing Sellers**
This visualization ranks the top 5 sellers based on total sales value. The bars represent total revenue contributed by each seller, providing clear insight into which vendors drive the most business. This chart supports vendor evaluation and relationship management decisions.
---
![ERD Scratch](https://github.com/Priyanka504595/Amazon_Analytics_Advanced_SQL_Project/blob/master/ERD_image.jpg)
**Orders with Pending Shipments**
This table view lists orders that have been paid for but are still awaiting shipment. It includes customer and shipping details, along with interactive filters for delivery and payment status. This visualization serves as a real-time operational tool for the logistics team to reduce shipment delays and improve customer satisfaction.
---
![ERD Scratch](https://github.com/Priyanka504595/Amazon_Analytics_Advanced_SQL_Project/blob/master/ERD_image.jpg)
**Average Order Value by Customer**
This bar chart displays customers ranked by their Average Order Value (AOV), giving insight into buyer behavior. Customers with higher AOVs are colored more intensely, making it easier to identify high-value individuals. This can help in targeting premium customers for loyalty programs or exclusive offers.
---
![ERD Scratch](https://github.com/Priyanka504595/Amazon_Analytics_Advanced_SQL_Project/blob/master/ERD_image.jpg)
**Customer Lifetime Value (CLTV)**
This chart illustrates the lifetime value of customers, calculated based on total purchases over time. Customers are listed with their ID and full name, and sorted by total revenue contribution. This view helps the business segment high-value customers, guide retention strategies, and personalize engagement.
---
### **Final Dashboard**
![ERD Scratch](https://github.com/Priyanka504595/Amazon_Analytics_Advanced_SQL_Project/blob/master/ERD_image.jpg)
The main Tableau dashboard consolidates multiple KPIs and visualizations: top-selling products, monthly sales trends, revenue by category, inventory alerts, seller performance, and pending shipments. KPI cards on the right highlight total revenue, total orders, and customer count. Filters provide interactivity for operations and executive stakeholders, enabling instant insights and data-driven decision-making.

---
## 📊 Dashboard Visualizations (in Tableau)

- ✅ Live SQL Server connection
- ✅ Fully interactive dashboards
- ✅ KPI Cards for AOV, CLTV, Pending Shipments, and Inventory
- ✅ Filter options by product, category, region, and payment status

---

## 🛠️ Tools & Tech Stack

- **SQL Server** – Database creation, querying, and procedure logic
- **Tableau Desktop** – Data visualization and dashboarding
- **Tableau Live Connection** – For real-time updates
- **VS Code + GitHub** – Code versioning and project management

---

## 🚀 Highlights

- 🔄 **Real-Time Dashboards**: Any updates in SQL data reflect instantly in Tableau
- 🧠 **Advanced Querying**: Solved 20+ business challenges using SQL alone
- 📦 **Stored Procedure**: Automatically deduct stock when a sale occurs
- 🎯 **Real-World Simulation**: Mimics Amazon's e-commerce backend and analysis pipeline

---


