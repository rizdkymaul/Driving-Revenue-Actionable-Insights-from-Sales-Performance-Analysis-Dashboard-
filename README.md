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
![alt text](https://github.com/rizdkymaul/Driving-Revenue-Actionable-Insights-from-Sales-Performance-Analysis-Dashboard-/blob/main/img/swot.jpg)

1. `Strength`

![alt text](https://github.com/rizdkymaul/Driving-Revenue-Actionable-Insights-from-Sales-Performance-Analysis-Dashboard-/blob/main/img/strength.jpg)

● Dominance of the "Robots" Category

The "Robots" category has the highest total sales, followed closely by the "Drones" category, reflecting strong demand and market appeal. This serves as a key driver of overall sales performance.

● Balanced Focus on Total Sales and Order Quantity

The "Drone Kits," "Training Videos," and "eBooks" categories also show significant order quantities, even though their total sales are not as high as those of the "Robots" category. This indicates potential opportunities to increase sales in these categories with the right marketing strategies.

● Affordable Yet Profitable

The "Training Videos" and "Blueprints" categories have lower total sales but outperform other categories in order quantity. This indicates a strong potential to boost sales in these categories through promotions or the development of more appealing products.

`Actionable Insight`

Develop a bundling strategy that combines products from the "Robots" category with "Drones" and "Training Videos." Offer attractive package deals that provide added value to customers, such as discounts on bundled purchases. This approach will not only drive sales in lower-performing categories but also strengthen customer loyalty and encourage repeat purchases.

2. `Weaknesses`

![alt text](https://github.com/rizdkymaul/Driving-Revenue-Actionable-Insights-from-Sales-Performance-Analysis-Dashboard-/blob/main/img/weakness.jpg)

● Product Offering Diversification
The "Robots" category dominates sales revenue. While this is a positive trend, it is important to remain cautious, especially given the decline in sales from 2020 to 2021. This downturn could significantly impact overall company revenue. Therefore, it is crucial to focus on other categories. This year, we can intensify promotions and campaigns for the "Drones" category, which has shown potential to offset the revenue decline from the "Robots" category.

`Actionable Insight`

Enhance promotions and marketing campaigns for the "Drones" category to drive sales growth. Develop compelling marketing strategies, such as exclusive discounts or product bundling, to capture customer interest and offset the revenue decline from the "Robots" category.

![alt text](https://github.com/rizdkymaul/Driving-Revenue-Actionable-Insights-from-Sales-Performance-Analysis-Dashboard-/blob/main/img/weakness.jpg)



