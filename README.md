# 📊 UrbanMart — E-commerce Sales & Profitability Analytics

## 🏢 About UrbanMart

UrbanMart is a multi-category online retail business that sells a wide range of everyday lifestyle and consumer products through multiple digital sales channels.

Its product portfolio includes categories such as Food & Beverage, Fitness, Home & Lifestyle, Electronics & Accessories, and other consumer products. Customers can purchase products through Shopee, Lazada, UrbanMart's website, and WhatsApp.

As UrbanMart operates across multiple product categories, regions, and sales channels, the business generates a diverse range of transactional data that can be used to evaluate its overall commercial performance.


## 📌 Project Overview

This project analyses UrbanMart's e-commerce transaction data to evaluate sales performance, product and regional performance, customer value, discount effectiveness, and profitability.

The project follows an end-to-end data analytics workflow, from data profiling and cleaning to exploratory data analysis, KPI development, data modelling, dashboard creation, and business recommendations.

---

## 🏢 Business Context

The company has transaction-level e-commerce data containing information such as:

- Order details
- Products & categories
- Customers
- Regions
- Sales channels
- Quantity & pricing
- Discounts
- Revenue
- Acquisition cost
- Profit
- Customer ratings

The objective is to transform raw transactional data into **actionable business insights** that can support better sales, marketing, customer, and profitability decisions.

---

## ❓ Problem Statement

### Business Problem / Objective

UrbanMart wants to better understand its sales and profitability performance across products, categories, regions, and customers. As sales are generated through multiple products and channels, the company needs a data-driven analysis to identify what drives revenue and profit, understand customer and regional performance, and evaluate the impact of discounts on sales and profitability. The analysis will provide actionable insights to support better pricing, product, customer, and sales strategies.

### Main Problem Statement

> The company lacks a consolidated and data-driven view of its e-commerce sales, customer, product, regional, and profitability performance. This makes it difficult for management to identify key revenue drivers, evaluate customer value, assess discount effectiveness, and identify opportunities to improve overall profitability.

---

## 🎯 SMART Objective

### Specific

Analyse e-commerce sales, customers, products, regions, discounts, and profitability.

### Measurable

Measure key business metrics including:

- Revenue
- Orders
- Unique Customers
- Average Order Value (AOV)
- Product & category contribution
- Regional performance
- Customer value
- Discount effectiveness
- Profit & profit margin

### Achievable

Use the available transaction dataset and Microsoft Excel to perform data cleaning, analysis, and visualization.

### Relevant

Generate actionable insights to improve sales performance, customer value, marketing effectiveness, and profitability.

### Time-Bound

Analyse business performance across the available reporting period.

### Objective

> To analyse e-commerce sales and customer transaction data over the available reporting period to identify key revenue drivers, customer segments, product and regional performance, discount effectiveness, and opportunities for improving sales and profitability.

---

## 🔍 Key Business Questions

This analysis aims to answer the following questions:

1. How is UrbanMart's overall sales and profitability performance?
2. Which products and categories are driving revenue and profit?
3. Which regions and sales channels perform best, and where are the opportunities for improvement?
4. Which customer segments contribute the most to UrbanMart’s sales and profitability?
5. How does discounting affect revenue and profitability?
6. What are the key drivers of UrbanMart's profitability, and where should the business focus to improve performance?

---

## 🧹 Data Profiling & Cleaning

### Data Profiling

The dataset was assessed for:

- Number of rows and columns
- Data types
- Missing values
- Duplicate records
- Unique values
- Invalid values
- Data consistency

### Data Cleaning

Data preparation was performed using **Power Query**, including:

- Removing duplicate records
- Handling missing values
- Standardising text values
- Correcting data types
- Standardising category names
- Handling unknown values
- Validating numerical columns

---

## 📐 Calculated Metrics

The following metrics were calculated to support the analysis.

### Revenue

Revenue = Quantity × Unit Price × (1 - Discount)

### Revenue per Customer

Revenue per Customer = Total Revenue ÷ Unique Customers

### Items per Order

Items per Order = Total Quantity ÷ Total Orders

Additional profitability metrics were also analysed:

- Total Profit
- Profit Margin
- Profit by Category
- Profit by Product
- Profit by Region

---

## 📊 Exploratory Data Analysis

### Sales Analysis

- Revenue by Month
- Revenue by Category
- Revenue by Product
- Revenue by Region
- Revenue by Sales Channel

### Customer Analysis

- Revenue by Customer
- Orders by Customer
- Customer Segmentation
- High-Value Customer Contribution

### Product Analysis

- Top Products by Revenue
- Top Products by Profit
- Category Revenue Contribution
- Category Profit Contribution

### Regional Analysis

- Revenue by Region
- Orders by Region
- AOV by Region
- Profit by Region

### Discount Analysis

- Discount vs Orders
- Discount vs Revenue
- Discount vs AOV
- Discount vs Profit
- Discount vs Profit Margin

---

## 📈 Dashboard

The dashboard provides a consolidated overview of the company's e-commerce performance.

### Key Performance Indicators

| KPI | Description |
|---|---|
| 💰 Total Revenue | Overall revenue generated |
| 🛒 Total Orders | Number of orders |
| 👥 Unique Customers | Number of customers |
| 📦 Total Quantity | Total units sold |
| 💵 AOV | Average revenue per order |
| 📈 Total Profit | Overall profit generated |
| 📊 Profit Margin | Profitability percentage |

### Dashboard Visuals

**1. Monthly Revenue Trend**  
→ Are sales increasing or decreasing over time?

**2. Revenue by Category**  
→ Which categories are the main revenue drivers?

**3. Top 10 Products**  
→ Which products contribute the most revenue?

**4. Revenue by Region**  
→ Which markets are performing best?

**5. Customer Segment**  
→ Which customer groups create the most value?

**6. Discount vs AOV / Orders**  
→ Is discounting effectively increasing sales?

**7. Profitability Analysis**  
→ Which products and categories generate the highest profit?

---

## Key Findings

### 1. Strong Overall Profitability

**Key Finding**  
UrbanMart generated **RM799.36K in sales and RM210.25K in profit**, achieving an overall **26.30% profit margin**. This indicates that the business is generating healthy profitability across its overall sales performance.

**Business Impact**  
The healthy profit margin indicates that UrbanMart is not only generating substantial sales but also converting a meaningful portion of its revenue into profit, providing a solid foundation for sustainable growth.

**Recommendation**  
Maintain the current profitability level by monitoring **costs, discounts, and product margins** while prioritising growth strategies that increase sales without significantly reducing profit margins.

---

### 2. Electronics is the Core Category, While Beauty Underperforms

**Key Finding**  
**Electronics** was the strongest category, generating **RM324.95K in sales, approximately RM91K in profit, and the highest profit margin at 28.07%**. In contrast, **Beauty generated approximately RM49K in sales and RM7K in profit**, with a significantly lower **14.08% margin**.

**Business Impact**  
Electronics is a major contributor to UrbanMart's revenue and profitability, while Beauty represents an underperforming category that may be limiting overall growth and profitability.

**Recommendation**  
Maintain strong inventory availability and marketing visibility for **Electronics**, while reviewing **Beauty's pricing, product mix, discounting, and cost structure** to identify opportunities for improving sales and profitability.

---

### 3. Monitor 24-inch is the Key Product

**Key Finding**  
The **Monitor 24-inch** was the top-performing individual product, ranking first in both **sales at approximately RM113K** and **profit at approximately RM39K**.

**Business Impact**  
The product makes a significant contribution to UrbanMart's overall sales and profit, making its performance important to the business's continued revenue generation.

**Recommendation**  
Prioritise **stock availability and demand monitoring** for the Monitor 24-inch while maintaining its visibility through appropriate marketing and promotional activities. Its strong performance can also provide a benchmark for identifying similar high-potential products.

---

### 4. Selangor is the Strongest Identifiable Market

**Key Finding**  
**Selangor** generated **RM201.01K in sales, RM55.02K in profit, and 482 orders**, making it the strongest identifiable region in UrbanMart's dataset.

**Business Impact**  
Selangor represents a major contribution to UrbanMart's sales and profitability, making it an important market for sustaining overall business performance.

**Recommendation**  
Maintain and strengthen market presence in **Selangor** through targeted marketing, product availability, and customer-focused strategies while exploring opportunities to improve performance in other regions.

---

### 5. Consumer Segment is the Core Customer Base

**Key Finding**  
Consumer customers generated **RM422.93K in net sales and RM113.25K in profit**, contributing approximately **68% of both total sales and profit**. Small Business followed with **RM125.69K in sales**, while Corporate contributed **RM70.28K**. This indicates that UrbanMart's overall performance is heavily driven by Consumer customers.

**Business Impact**  
UrbanMart is highly dependent on the Consumer segment, making customer retention and repeat purchases within this segment important to sustaining revenue. At the same time, the lower contribution from Corporate and Small Business segments presents an opportunity to diversify the customer base.

**Recommendation**  
Strengthen **Consumer-focused retention and promotional strategies** while developing targeted offerings for **Corporate and Small Business segments** to diversify revenue sources and reduce dependency on a single customer segment.

---

### 6. Key Drivers of Profitability and Areas for Improvement

**Key Finding**  
UrbanMart generated **RM210.25K in profit with a 26.30% overall profit margin**. **Electronics** was the strongest category, generating **RM324.95K in sales** with the highest **28.07% profit margin**, while the **Monitor 24-inch** was the top individual product, contributing approximately **RM113K in sales and RM39K in profit**. In contrast, **Beauty** underperformed, generating approximately **RM49K in sales** with a low **14.08% profit margin**. **Selangor** was also the strongest identifiable market, contributing **RM201.01K in sales and RM55.02K in profit**.

**Business Impact**  
UrbanMart's profitability is strongly supported by high-performing categories, products, and markets. However, the significant performance gap between Electronics and Beauty indicates potential profitability and growth opportunities within underperforming areas.

**Recommendation**  
Maintain inventory and marketing focus on high-performing **Electronics products**, particularly the **Monitor 24-inch**, while strengthening market presence in **Selangor**. Review **Beauty's pricing, product mix, discounting, and cost structure** to identify opportunities to improve its low profit margin.

---

## 🛠️ Tools & Technologies

### Tools

- Microsoft Excel
- Power Query
- Excel Tables
- PivotTables
- PivotCharts
- Excel Formulas
- Conditional Formatting
- Excel Dashboard

### Analytical Skills

- Data Cleaning
- Data Transformation
- Exploratory Data Analysis (EDA)
- KPI Analysis
- Customer Analysis
- Product Analysis
- Regional Analysis
- Profitability Analysis
- Discount Analysis
- Data Visualization
- Business Insight Generation
