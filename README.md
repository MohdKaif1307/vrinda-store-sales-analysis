# Vrinda Store Sales Analysis - 2022 Annual Report

An end-to-end data analysis project analyzing 31,000+ sales transactions from Vrinda Store's 2022 operations using Microsoft Excel. This project demonstrates data cleaning, exploratory data analysis (EDA), pivot table creation, and interactive dashboard development for business intelligence.

## 📊 Project Overview

Comprehensive analysis of Vrinda Store's e-commerce sales performance across multiple channels (Amazon, Flipkart, Myntra, Ajio, Meesho) to identify key trends, customer demographics, and actionable insights for strategic planning.

## 🎯 Business Objectives

- Analyze sales trends across months to identify peak and low-performing periods
- Understand customer demographics (gender, age groups) and purchasing patterns
- Identify top-performing states for targeted marketing campaigns
- Compare sales channels to optimize marketing spend
- Analyze order fulfillment status to improve operational efficiency

## 📁 Dataset Overview

**Size:** 31,048 rows × 21 columns  
**Period:** January 2022 - December 2022  
**Geography:** Pan-India (all states)

### Data Fields:
- **Order Details:** Order ID, Customer ID, Date, Month, Status
- **Customer Info:** Gender, Age, Age Category
- **Product Info:** SKU, Category, Size, Quantity, Amount
- **Shipping:** City, State, Postal Code, Country
- **Channel:** Amazon, Flipkart, Myntra, Ajio, Meesho, Nalli, Others
- **Business Type:** B2B Flag

## 🔍 Key Insights & Findings

### 1. Gender-Based Purchasing Behavior
- **Women:** ₹13,562,773 (64.04% of total sales)
- **Men:** ₹7,613,604 (35.96% of total sales)
- **Key Insight:** Women are the primary customer segment, contributing nearly 2x more revenue

### 2. Order Fulfillment Analysis
- **Delivered:** 28,641 orders (92.25%)
- **Returned:** 1,045 orders (3.37%)
- **Cancelled:** 844 orders (2.72%)
- **Refunded:** 517 orders (1.66%)
- **Success Rate:** 92.25% delivery success

### 3. Top 5 Performing States
| Rank | State | Revenue (₹) |
|------|-------|-------------|
| 1 | Maharashtra | 2,990,221 |
| 2 | Karnataka | 2,646,358 |
| 3 | Uttar Pradesh | 2,104,659 |
| 4 | Telangana | 1,712,439 |
| 5 | Tamil Nadu | 1,678,877 |

### 4. Age & Gender Distribution
- **Adult Women (30-49):** 34.59% (highest segment)
- **Teenager Women (18-29):** 21.13%
- **Adult Men (30-49):** 15.47%
- **Senior Women (50+):** 13.70%
- **Key Insight:** Women aged 30-49 represent the core customer base

### 5. Sales Channel Performance
| Channel | Order Share |
|---------|-------------|
| Amazon | 35.48% |
| Myntra | 23.36% |
| Flipkart | 21.59% |
| Ajio | 6.22% |
| Nalli | 4.78% |
| Meesho | 4.50% |
| Others | 4.06% |

**Top 3 Channels:** Amazon, Myntra, Flipkart (80.43% combined)

### 6. Monthly Sales Trends
- **Peak Month:** March 2022 (₹1,928,066 | 2,819 orders)
- **Lowest Month:** December 2022 (₹1,622,033 | 2,384 orders)
- **Average Monthly Revenue:** ₹1,764,698
- **Trend:** Declining sales in Q4 2022 (Sep-Dec)

## 🛠️ Tools & Techniques

### Microsoft Excel Features Used:
- **Data Cleaning:** Removed duplicates, handled missing values, standardized formats
- **Pivot Tables:** Created 7 pivot tables for multi-dimensional analysis
- **Charts & Visualizations:** Bar charts, pie charts, line graphs
- **Dashboard:** Interactive dashboard with slicers for filtering
- **Functions:** VLOOKUP, SUMIF, COUNTIF, date functions
- **Conditional Formatting:** Highlight top performers and trends

## 📈 Dashboard Features

Interactive dashboard includes:
- Monthly sales and order trends (line chart)
- Gender-wise sales comparison (pie chart)
- Top 5 states by revenue (bar chart)
- Channel performance breakdown (pie chart)
- Age-gender distribution matrix
- Order status distribution
- Dynamic filters for Month, Channel, Category

## 💡 Business Recommendations

1. **Target Women Aged 30-49:** Focus marketing campaigns on this demographic for maximum ROI
2. **Strengthen Top 3 Channels:** Invest more in Amazon, Myntra, and Flipkart partnerships
3. **Geographic Expansion:** Prioritize Maharashtra, Karnataka, and UP for warehouse/logistics
4. **Seasonal Strategy:** Investigate Q4 decline and plan promotional campaigns
5. **Reduce Returns:** 3.37% return rate needs attention - improve product descriptions and quality control

## 📂 Repository Structure

