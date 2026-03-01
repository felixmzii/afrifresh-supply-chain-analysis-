# AfriFresh Supply Chain, Logistics, Inventory and Sales Analytics Report

## Executive Summary

This report presents a comprehensive analysis of AfriFresh’s supply chain operations, including sales performance, logistics efficiency, inventory management, and warehouse operations. The analysis was conducted using Microsoft Excel and integrates data from multiple operational areas to provide management with actionable insights.

The project involved building a structured data model, calculating key performance indicators (KPIs), performing business and statistical analysis, and developing an interactive dashboard to support decision-making.

Key findings indicate that AfriFresh is operating with a healthy profit margin, efficient delivery timelines, and strong performance in selected product categories and warehouse locations. However, opportunities exist to optimize inventory allocation, improve profitability in lower-performing categories, and further enhance operational efficiency.

This dashboard provides management with a real-time tool to monitor performance and make data-driven strategic decisions.

---

## 1. Introduction

Supply chain analytics is critical for organizations that depend on efficient inventory management, logistics operations, and sales performance. AfriFresh operates across multiple warehouses and distributes various product categories, requiring effective coordination between procurement, storage, and delivery operations.

The purpose of this project was to analyze AfriFresh’s operational data and develop a professional analytics dashboard to provide visibility into key performance areas, including profitability, inventory value, warehouse performance, and delivery efficiency.

The analysis transforms raw operational data into meaningful insights to support strategic planning and operational improvements.

---

## 2. Project Objectives

The main objectives of this project were:

• To analyze overall sales revenue and profit performance
• To evaluate warehouse efficiency and profitability
• To assess inventory levels and identify optimization opportunities
• To measure logistics performance using delivery timelines
• To identify the most and least profitable product categories
• To build an interactive Excel dashboard for management monitoring
• To provide actionable recommendations based on data insights

---

## 3. Dataset Description

The dataset consists of multiple related tables representing AfriFresh’s supply chain operations. These tables are linked using unique identifiers to ensure accurate analysis and relational integrity.

### Tables included:

**Orders Table**
Contains information about customer orders, including OrderID, OrderDate, and WarehouseID.

**Order Details Table**
Contains transactional sales data, including:

• ProductID
• Quantity Sold
• Unit Price
• Revenue
• Cost
• Profit

**Inventory Table**
Contains stock information including:

• ProductID
• WarehouseID
• Quantity in stock
• Inventory Value

**Shipments Table**
Contains logistics performance data including:

• ShipmentID
• OrderID
• Delivery Days

**Warehouses Table**
Contains warehouse location and regional information.

**Products Table**
Contains product information including:

• Product Name
• Category
• Standard Price

All tables are connected using unique IDs such as OrderID, ProductID, and WarehouseID.

---

## 4. Data Modeling and Relationships

To enable accurate analysis, relationships were established between tables using unique identifiers:

• Orders linked to Order Details using OrderID
• Order Details linked to Products using ProductID
• Orders linked to Warehouses using WarehouseID
• Shipments linked to Orders using OrderID
• Inventory linked to Products and Warehouses

This relational structure ensures accurate aggregation and reporting across multiple operational areas.

---

## 5. Key Performance Indicators (KPIs)

The following KPIs were calculated to measure business performance:

### Total Revenue

Measures total sales generated across all products and warehouses.

Importance: Indicates overall business growth and sales performance.

---

### Total Profit

Measures total profit generated after deducting costs.

Importance: Indicates financial performance and business sustainability.

---

### Profit Margin

Calculated as:

Profit Margin = Total Profit / Total Revenue

Importance: Measures efficiency and profitability.

---

### Total Orders

Counts total number of unique customer orders.

Importance: Measures business activity level.

---

### Inventory Value

Measures total monetary value of all stock across warehouses.

Importance: Indicates capital tied up in inventory.

---

### Average Delivery Days

Measures average delivery time for shipments.

Importance: Indicates logistics efficiency and customer service quality.

---

## 6. Dashboard Development

An interactive Excel dashboard was developed to allow management to monitor performance dynamically.

### Dashboard features include:

• KPI cards displaying key business metrics
• Profit analysis by warehouse
• Profit analysis by product category
• Inventory value monitoring
• Delivery performance tracking

### Interactive Filters (Slicers):

• Warehouse
• Product Category
• Product Name
• Region

These filters allow management to analyze performance across different operational segments.

---

## 7. Data Analysis and Findings

The analysis revealed several important performance trends:

### Profitability Analysis

AfriFresh operates with a healthy profit margin, indicating effective pricing and cost management.

However, profitability varies across warehouses and product categories.

Some warehouses generate significantly higher profit than others.

---

### Warehouse Performance

Certain warehouses outperform others due to:

• Higher sales volume
• Better product mix
• Strong regional demand

Lower-performing warehouses may require operational review.

---

### Product Category Performance

Some product categories generate higher profit margins.

Lower-performing categories may have:

• Lower demand
• Higher cost
• Lower pricing efficiency

This presents opportunities for optimization.

---

### Inventory Analysis

Inventory value is significant, indicating capital investment in stock.

Opportunities exist to optimize stock levels and reduce slow-moving inventory.

---

### Logistics Performance

Average delivery time is within acceptable operational standards.

Efficient delivery contributes to customer satisfaction and operational efficiency.

---

## 8. Business Insights

The analysis provides several critical business insights:

• Profitability varies significantly by warehouse
• Certain product categories contribute most to profit
• Inventory optimization can improve cash flow
• Efficient delivery operations support customer satisfaction
• Dashboard enables real-time performance monitoring

These insights enable data-driven decision-making.

---

## 9. Business Recommendations

Based on the analysis, the following recommendations are proposed:

### Operational Recommendations

• Increase stock allocation to high-performing warehouses
• Improve performance of lower-performing warehouses
• Optimize product distribution

---

### Financial Recommendations

• Focus on high-profit product categories
• Review pricing strategies for low-profit products
• Monitor profit margin continuously

---

### Inventory Recommendations

• Reduce slow-moving inventory
• Implement demand-based stock planning
• Improve inventory turnover

---

### Logistics Recommendations

• Maintain efficient delivery timelines
• Optimize delivery routes
• Improve coordination between warehouses

---

## 10. Dashboard Value to Management

The dashboard provides management with:

• Real-time performance monitoring
• Profitability tracking
• Inventory visibility
• Operational efficiency insights
• Decision-support capabilities

This improves strategic and operational decision-making.

---

## 11. Project Tools and Technologies

The following tools were used:

• Microsoft Excel
• Pivot Tables
• Excel Dashboard Design
• Data Modeling
• KPI Development
• Business Analysis

---

## 12. Conclusion

This project successfully demonstrates the use of Excel to analyze supply chain, logistics, inventory, and sales data.

The interactive dashboard provides management with clear visibility into business performance and supports data-driven decision-making.

The analysis identified opportunities to improve profitability, optimize inventory, and enhance operational efficiency.

This solution can be further enhanced using advanced tools such as SQL, Power BI, and Python for enterprise-level analytics.

---

## 13. Author

Felix Ondari
Data Analyst – Supply Chain Analytics
Excel Dashboard and Business Intelligence Specialist
