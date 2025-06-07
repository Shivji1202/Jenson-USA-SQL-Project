# BikeStores Sample Database & Jenson USA SQL Analysis


This repository features a complete **BikeStores** sample database setup and a comprehensive **SQL project** based on real-world analytical use cases from **Jenson USA**, an e-commerce and brick-and-mortar cycling retailer.

---

## Contents

-  [`create objects.sql`](./BikeStores%20Sample%20Database%20-%20create%20objects.sql): Script to create all tables and constraints  
-  [`load data.sql`](./BikeStores%20Sample%20Database%20-%20load%20data.sql): Script to insert sample data  
-  [`Jenson USA_SQL_Projects.pdf`](./Jenson%20USA_SQL_Projects.pdf): PDF containing business questions, insights, and query examples

---

## Database Structure

**Tables Created:**
- Products: `brands`, `categories`, `products`
- Sales: `customers`, `orders`, `order_items`
- Operations: `stores`, `staffs`, `stocks`

**Relationships:**
- Product-category-brand hierarchy  
- Staff → Store, Orders → Customers → Items  
- Proper foreign key constraints with cascading actions

---

## Business Objectives

Key metrics and KPIs targeted:

| Focus Area         | Objectives                                                                 |
|--------------------|---------------------------------------------------------------------------|
|  Customer Behavior | Preferences, order history, product category coverage                     |
|  Staff Performance | Identify top/low performers, find staff with zero sales                  |
|  Store Operations  | Total sales, inventory status, category-wise performance                  |
|  Inventory Flow    | Out-of-stock alerts, stock level efficiency                              |


## Why This Analysis Matters?

In a competitive retail and e-commerce environment, data-driven decision-making is essential. This project applies SQL analysis to real-world business questions to drive insights and actions in the following areas:

### 1. Customer Behavior
Understand preferences, buying patterns, and customer journeys.
- Target marketing efforts
- Identify loyal or high-spending customers
- Tailor product offerings

### 2. Inventory Management
Optimize stock levels and avoid product shortages or overstock.
- Highlight unsold products
- Track high-demand items
- Improve supply chain efficiency

### 3. Staff Performance
Measure employee impact and sales contribution.
- Identify top and underperforming staff
- Support performance reviews and training plans

### 4. Store Operations
Evaluate the health of each location and its contribution to overall sales.
- Compare regional sales performance
- Improve resource allocation
- Optimize promotions and staffing

### The Goal
Empower decision-makers with clear, actionable insights to:
- Increase revenue
- Improve efficiency
- Enhance customer satisfaction

