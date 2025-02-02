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

# ERD Diagram
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

# Query Create Master Table

![alt text](https://github.com/rizdkymaul/Driving-Revenue-Actionable-Insights-from-Sales-Performance-Analysis-Dashboard-/blob/main/img/query.jpg)
:::

# Sales Performance Dashboard

![alt text](https://github.com/rizdkymaul/Driving-Revenue-Actionable-Insights-from-Sales-Performance-Analysis-Dashboard-/blob/main/img/sales_performance_dashboard.jpg)

[Made with Looker Studio](https://lookerstudio.google.com/reporting/271fc6f2-f1d6-49cd-a7c9-dca928a354a7)

# SWOT Analysis
![alt text](https://github.com/rizdkymaul/Driving-Revenue-Actionable-Insights-from-Sales-Performance-Analysis-Dashboard-/blob/main/img/swot.jpg)

`1. Strength`

![alt text](https://github.com/rizdkymaul/Driving-Revenue-Actionable-Insights-from-Sales-Performance-Analysis-Dashboard-/blob/main/img/strength.jpg)

● Dominance of the "Robots" Category

The "Robots" category has the highest total sales, followed closely by the "Drones" category, reflecting strong demand and market appeal. This serves as a key driver of overall sales performance.

● Balanced Focus on Total Sales and Order Quantity

The "Drone Kits," "Training Videos," and "eBooks" categories also show significant order quantities, even though their total sales are not as high as those of the "Robots" category. This indicates potential opportunities to increase sales in these categories with the right marketing strategies.

● Affordable Yet Profitable

The "Training Videos" and "Blueprints" categories have lower total sales but outperform other categories in order quantity. This indicates a strong potential to boost sales in these categories through promotions or the development of more appealing products.

`Actionable Insight`

Develop a bundling strategy that combines products from the "Robots" category with "Drones" and "Training Videos." Offer attractive package deals that provide added value to customers, such as discounts on bundled purchases. This approach will not only drive sales in lower-performing categories but also strengthen customer loyalty and encourage repeat purchases.

`2. Weaknesses`

![alt text](https://github.com/rizdkymaul/Driving-Revenue-Actionable-Insights-from-Sales-Performance-Analysis-Dashboard-/blob/main/img/weakness.jpg)

● Product Offering Diversification
The "Robots" category dominates sales revenue. While this is a positive trend, it is important to remain cautious, especially given the decline in sales from 2020 to 2021. This downturn could significantly impact overall company revenue. Therefore, it is crucial to focus on other categories. This year, we can intensify promotions and campaigns for the "Drones" category, which has shown potential to offset the revenue decline from the "Robots" category.

`Actionable Insight`

Enhance promotions and marketing campaigns for the "Drones" category to drive sales growth. Develop compelling marketing strategies, such as exclusive discounts or product bundling, to capture customer interest and offset the revenue decline from the "Robots" category.

![alt text](https://github.com/rizdkymaul/Driving-Revenue-Actionable-Insights-from-Sales-Performance-Analysis-Dashboard-/blob/main/img/weakness%202.jpg)

● Cross-Selling & Upselling

Leverage existing customers by offering products from the "eBooks" and "Blueprints" categories when they purchase items from the "Robots" category. This strategy can be implemented through SEO-driven product recommendations on e-commerce platforms, websites, or targeted email marketing campaigns.

● Product Bundling

Develop a bundling strategy that provides attractive options for new customers purchasing products in the "Robots" and "Drones" categories. Offer special deals when bundled with products from the "eBooks" and "Blueprints" categories. This approach enhances the overall shopping experience while boosting sales in the "eBooks" and "Blueprints" categories.

`Actionable Insight`

Design an effective cross-selling and upselling strategy with SEO-based product recommendations on e-commerce platforms and email marketing campaigns. Additionally, create attractive bundling packages for new customers shopping in the Robots and Drones categories, offering incentives such as discounts or bonus products to increase transaction value.

`3. Opportunities`

![alt text](https://github.com/rizdkymaul/Driving-Revenue-Actionable-Insights-from-Sales-Performance-Analysis-Dashboard-/blob/main/img/opportunities.jpg)

● Launch New Products
Leverage sales distribution in the Washington area to launch new products. This can create new opportunities to drive company sales growth.

● Expand Promotional Strategies
Optimize promotional strategies in regions with order volumes between 100 and 200 and total sales ranging from $20,000 to $30,000 USD. Cities such as Houston, Miami, El Paso, and Birmingham present the most promising markets for sales expansion.

● With a diverse product lineup, there is a significant opportunity to enhance and expand promotional efforts. Utilize digital marketing strategies to drive this sales expansion effectively.

`Actionable Insight`

Leverage these regions to introduce new products. Additionally, optimize promotional strategies in cities with order volumes between 100 and 200 and total sales of approximately $20,000 to $30,000 USD, such as Houston, Miami, El Paso, and Birmingham. Design compelling and relevant marketing campaigns to capture customer attention in these markets.

4. Threats

![alt text](https://github.com/rizdkymaul/Driving-Revenue-Actionable-Insights-from-Sales-Performance-Analysis-Dashboard-/blob/main/img/threatness.jpg)

● Leveraging Customer Loyalty to Stay Competitive
Customer sdixceekl has the highest loyalty score (7) but a relatively low total purchase amount ($236). In contrast, customer hfaulconerbv has a loyalty score of 6 with a significantly higher total purchase amount ($1,611). This indicates that some customers, despite not having the highest loyalty scores, still make a substantial contribution to revenue.

` Actionable Insight`

● Gamified Loyalty Program
Develop a gamified loyalty program with tiers, reward points, badges, and challenges. Integrate it with a mobile app for easy access and higher engagement. Offer attractive rewards and opportunities to redeem points for products or discounts.

● User-Generated Content & Influencer Marketing
Encourage customers to create content about products (e.g., reviews, photos, videos) and provide incentives. Partner with micro-influencers relevant to the target market to boost brand awareness and social proof.

● Exclusive Community for Top Customers
Create an exclusive online community (e.g., Facebook groups, Discord) or offline events for top customers. Provide exclusive access to content, new products, and opportunities to interact with the company. This will strengthen loyalty and brand advocacy.
