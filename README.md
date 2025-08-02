# 📊 DVDRental Dashboard – Power BI Project
Author: Hessam Abedinpour
Tool: Microsoft Power BI
Dataset: PostgreSQL - DVDRental Sample Database
File: HW-L04-01-PowerBI-Hessam-Abedinpour.pbix

# 🧩 Overview
This Power BI dashboard was built using the DVDRental sample database to provide an interactive overview of key business insights for a DVD rental company. The dashboard is designed to help stakeholders monitor business performance, customer behavior, and sales trends.

# 📌 Key Features
. KPI Cards: Total revenue, number of rentals, active customers, and average payment amount.
# Bar Charts:
. Top 10 cities by revenue.
. Revenue by film category.
# Line/Area Chart:
. Monthly revenue trend to track performance over time.
# Pie/Donut Charts:
. Revenue distribution by store or customer location.
# Tables and Tooltips:
. Detailed transaction tables with drill-through capability.

# 🔐 Row-Level Security (RLS)
This dashboard includes Row-Level Security (RLS) to restrict data access based on user roles. RLS ensures that each user can only see the data they are authorized to access — for example, data filtered by store, city, or customer.
# 📌 Implementation Details:
. A role (e.g., StoreManager) was created using DAX filters.
. The filter is applied to the relevant table(s), such as store, customer, or rental, to limit visibility.
. When a user is assigned to a specific role, Power BI dynamically filters the data based on the defined rules.
# 🧪 Example Use Case:
A manager from Store 1 can only view rental and sales data related to their store and customers. They won’t see data from other stores.
This setup improves data security, compliance, and provides a personalized user experience within the same report. 

# 🔍 Data Sources Used
The dashboard uses data from the following tables:
. customer
. payment
. rental
. inventory
. film
. category
. City, country, and store
Data was pre-cleaned and loaded into Power BI using Power Query.

# 💡 Insights Highlighted
. Most profitable cities and countries
. Best-performing film categories
. Customer distribution and payment behavior
. Revenue trends over time

# ⚙️ Technologies
. Power BI Desktop
. Power Query (ETL)
. DAX for measures and calculated columns
. PostgreSQL (source schema: dvdrental)

# 📁 File
dvdrental.pbix — the full Power BI dashboard file
