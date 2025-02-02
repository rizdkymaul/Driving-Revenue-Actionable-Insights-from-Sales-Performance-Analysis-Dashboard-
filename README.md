**Project - Based Virtual Internship: Business Intelligence Analyst Bank Muamalat x Rakamin Academy**

# **Driving Revenue-Actionable Insights from Sales Performance Analysis**
**Sales Performance Dashboard**

**Periode 1 Jan 2020 - 31 Dec 2021** 
**PT. Sejahtera Bersama**

**By Muhammad Rizdky Maulady**


[4 Dataset](https://github.com/rizdkymaul/Driving-Revenue-Actionable-Insights-from-Sales-Performance-Analysis-Dashboard-/tree/main/dataset "4 Dataset")

[Query](https://github.com/rizdkymaul/Driving-Revenue-Actionable-Insights-from-Sales-Performance-Analysis-Dashboard-/blob/main/query_sales_master.txt"Query")

:::
# CASE

# `Primary Key, Relationship & Join Tables`

● Determine each primary key in the 4 datasets

● Relationship of the 4 tables

● Join to Create table master sales Performance

# `Sales Performance Dashboard`

● Dashboard Features

# `Maintain & Increase Sales`

● SWOT Analysis & Actionable Insights

:::
#ERD Diagram
![alt text](https://github.com/rizdkymaul/Driving-Revenue-Actionable-Insights-from-Sales-Performance-Analysis-Dashboard-/blob/main/img/erd.jpg)

`Primary Key`
1. Customers Table
Primary key : Customer ID
2.  Orders Table
Primary key : OrderID
Foreign key : CustomerID, ProdNumber
3. Products Table 
Primary key : ProdNumber
Foreign key : Category
4. Product Category Table
Primary key : CategoryID 

`Relationship`

1.Customers (c) to Orders (o)

● One to Many (CustomerID c to  CustomerID o)

2. Products (p) to Orders (o)
    
● One to Many (ProdNumber o to ProdNumber p)

4. Products (p) to Product Category (pc)
   
● Many to One (ProdNumber o to ProdNumber p﻿)

#Query Create Master Table

![alt text](https://github.com/rizdkymaul/Driving-Revenue-Actionable-Insights-from-Sales-Performance-Analysis-Dashboard-/blob/main/img/query.jpg)
:::

#Sales Performance Dashboard

![alt text](https://github.com/rizdkymaul/Driving-Revenue-Actionable-Insights-from-Sales-Performance-Analysis-Dashboard-/blob/main/img/sales_performance_dashboard.jpg)

[Made with Looker Studio](https://lookerstudio.google.com/reporting/271fc6f2-f1d6-49cd-a7c9-dca928a354a7)

# SWOT Analysis
`Strength`
**Total sales reached $1,754,751 USD**

`What are the key factors contributing to this high sales performance?`
