# Apparel Store Report

## Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Process](#process)
- [Features](#features)
- [Insights](#insights)
- [Learning](#learning)

## Overview

A Clothing store wants to create an annual sales report for Year 2022. So that, they can understand their customers and grow more sales in the next year 2023.  

![Overview 1](https://github.com/user-attachments/assets/c0b6b841-06dd-4e41-b360-a90a0f7120a7)  


![Overview 2](https://github.com/user-attachments/assets/c034b742-53d5-4ea9-a24e-485bd7ab1224)  


## Dataset

**Clothing Shop Sales**

Transaction records for an Apparel Store, a clothing shop operating out of India. Dataset includes the transaction date, timestamp and location, along with product-level details.  

**Dataset Explanation** 

- **index:** The sequential number of the row or entry in the dataset.
- **Order ID:** A unique identifier assigned to each customer order.
- **Cust ID:** The unique ID identifying the customer who placed the order.
- **Gender:** The gender of the customer (e.g., Women).
- **Age:** The age of the customer at the time of the order.
- **Date:** The date the order was placed or processed (may be masked in the given row).
- **Status:** The current delivery status of the order (e.g., Delivered).
- **Channel:** The sales platform or channel through which the order was placed (e.g., Myntra).
- **SKU:** The Stock Keeping Unit, a unique code to identify each specific product variant.
- **Category:** The general product category (e.g., kurta).
- **Size:** The size of the product ordered (e.g., XXL).
- **Qty:** The quantity of units ordered for this line item.
- **currency:** The currency used for the transaction (e.g., INR).
- **Amount:** The total amount or price for this line item.
- **ship-city:** The city to which the product was shipped (e.g., MOHALI).
- **ship-state:** The state where the shipping address is located (e.g., PUNJAB).
- **ship-postal-code:** The postal or pin code for the shipping address.
- **ship-country:** The country of the shipping address (e.g., IN).
- **B2B:** Indicates whether the order is a "business-to-business" transaction (TRUE or FALSE).


## Process

Tools Used :- Microsoft Excel  

Process:-   
-Familiarizing with the dataset.  
-Checking for any NULL values or Data errors.  
-Using calculations to generate the required columns.  
-Using Pivot Tables to analyze the data.  
-Inserting Slicers for convenience.  
-Generate Pivot Charts and gain Insights.  
-Making the Dashboard.  

## Features

### 1. **Revenue & Transactions Breakdown**

### 2. **Product Category & Best Sellers**

### 3. **Customer Behavior and Segments**

### 4. **Strategic Recommendations**

## Insights

Here are key insights based on the provided pivot tables from your order and revenue data:

## Overall Performance

- **Total Orders:** 31,047
- **Total Revenue:** ₹21,441,209

## Product Performance

- **Most Sold Category:** "Set" leads with 12,446 units sold, followed by "Kurta" (10,541 units), "Western Dress" (4,084 units), "Top" (2,201 units), and "Saree" (1,389 units).
- **Least Sold Category:** "Bottom" (78 units), "Blouse" (234 units).

## Sales Trends by Month

| Month      | Revenue      | Orders  |
|------------|:------------:|:-------:|
| January    | 1,839,113    | 2,702   |
| February   | 1,900,550    | 2,750   |
| March      | 1,961,232    | 2,819   |
| April      | 1,854,665    | 2,685   |
| May        | 1,833,460    | 2,617   |
| June       | 1,768,326    | 2,597   |
| July       | 1,794,794    | 2,579   |
| August     | 1,826,937    | 2,617   |
| September  | 1,715,429    | 2,490   |
| October    | 1,682,862    | 2,424   |
| November   | 1,634,756    | 2,383   |
| December   | 1,629,085    | 2,384   |

- **Highest Revenue Month:** March
- **Lowest Revenue Month:** December

## Customer Segmentation by Gender

- **Women's Segment:** ₹13,756,251 revenue (≈64% of total)
- **Men's Segment:** ₹7,684,958 revenue (≈36% of total)
- **Women drive a significantly larger share of revenue.**

## Order Status Distribution

- **Delivered:** 28,641 orders (most common)
- **Cancelled:** 844 orders
- **Returned:** 1,045 orders
- **Refunded:** 517 orders

## Geographic Distribution

- **Top Revenue States:**
  - Maharashtra: ₹3,011,677
  - Karnataka: ₹2,690,050
  - Uttar Pradesh: ₹2,147,265
  - Telangana: ₹1,731,869
  - Tamil Nadu: ₹1,720,783

## Age Group & Gender Mix (by Percentage of Orders)

| Age Group | Men    | Women  |
|-----------|--------|--------|
| Adult     | 15.47% | 34.59% |
| Senior    | 5.91%  | 13.70% |
| Teenager  | 9.20%  | 21.13% |

- **Largest segment:** Adult women (34.59%), followed by women teenagers (21.13%).

## Channel Performance (Order Share)

| Channel   | Orders (%) |
|-----------|------------|
| Amazon    | 35.5       |
| Myntra    | 23.4       |
| Flipkart  | 21.6       |
| Nalli     | 4.8        |
| Ajio      | 6.2        |
| Meesho    | 4.5        |
| Others    | 4.1        |

- **Top Performing Channel:** Amazon, accounting for over a third of all orders.
- **Secondary Channels:** Myntra and Flipkart also have significant shares.

### Key Insights Summary

- The majority of sales are driven by women, especially adults.
- "Set" and "Kurta" are the most popular product categories.
- Maharashtra and Karnataka are the top contributing states in revenue.
- Amazon is the leading sales channel.
- Most orders are delivered successfully, but there is a measurable rate of cancellation and returns, suggesting review opportunities for fulfillment or product satisfaction.
- March is traditionally the highest revenue month, while December is the lowest.

These insights can help target future marketing campaigns, optimize product mix, improve fulfillment strategies, and prioritize regions and channels for better overall performance.


## Learning

### 1. **Data Analysis & Interpretation**
- Ability to work with raw sales data to generate meaningful **pivot tables** and derive actionable **insights**.
- Proficiency in identifying key business trends such as seasonality, customer behavior by time, and product performance.

### 2. **Dashboard Design & Data Visualization**
- Experience designing **interactive dashboards** with features tailored to business needs.  
- Skill in selecting appropriate **visualization types** for different analytical questions.

### 3. **Business Intelligence Application**
- Translating analytical results into **actionable business recommendations** (e.g., focus points for promotions, operational optimizations).
- Understanding how analytics can inform real-world decisions in retail/clothing service.

### 4. **Product and Customer Analytics**
- Ability to segment products and customers, identify bestsellers, and interpret customer preferences.  

This project showcases my ability to analyze complex retail sales data, design an interactive and insight-driven dashboard, and make actionable recommendations for business growth. Through advanced use of pivot tables, visualization tools, and business intelligence concepts, I developed an end-to-end analytics solution that reveals critical patterns in customer behavior, peak sales periods, and product performance. This project deepened my understanding of retail analytics, and refined my talent for transforming raw data into compelling, business-relevant stories.
