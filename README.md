# 📊 Silver Analytics — Power BI Dashboard

![Dashboard Preview](screenshots/page1_executive_summary.png)

## 🔗 Live Dashboard
[👉 Click here to view the live dashboard](https://sonatechac-my.sharepoint.com/:u:/g/personal/manasvisharadmali_23cse_sonatech_ac_in/IQDHJVSxH01fSY9jaVlwlUMrATiVk79cX11OqrULSwDaMsw?e=MHxaKQ)

---

## 📌 Project Overview
End-to-end Power BI analytics dashboard built for a 
silver retail business. Tracks sales performance, 
inventory health, revenue trends, and customer behaviour 
across FY 2023-24 (April 2023 – March 2024).

Built to demonstrate Business Analyst, Data Analyst, 
and Product Analyst skills including data modelling, 
DAX, and insight generation.

---

## 📁 Dashboard Pages

| Page | Description |
|------|-------------|
| Executive Summary | 5 KPI cards, monthly revenue trend, slicers |
| Sales Analytics | Revenue by category, segment donut, top 10 products |
| Inventory Analytics | Stock levels, turnover rate, low stock alerts |
| Business Insights | Analyst commentary, MoM growth, geographic analysis |

---

## 📂 Dataset Details

| Table | Rows | Description |
|-------|------|-------------|
| Sales_Transactions | 560 | FY 2023-24 sales records |
| Customers | 50 | 3 segments — Retail, Wholesale, Online |
| Product_Master | 15 | SKUs across 6 jewellery categories |
| Inventory | 15 | Stock levels, turnover, reorder alerts |

**Business rules built into data:**
- Festival season (Oct–Dec) seasonality
- Wholesale customers get 15% discount
- Indian Financial Year (Apr–Mar) structure

---

## ⚡ DAX Measures (15 total)

**Revenue & Profit**
- Total Revenue, Total Gross Profit
- Gross Margin %, Avg Order Value

**Time Intelligence**
- Revenue Last Month, Revenue MoM Growth %
- Revenue YTD, Revenue PYTD

**Inventory**
- Total Stock Value, Low Stock Items
- Avg Inventory Turnover, Total Units Sold

**Customer**
- Unique Customers, Avg Revenue Per Customer
- Total Orders

---

## 🔍 Key Business Insights

- Festival season (Oct–Dec) drives peak revenue —
  November recorded highest monthly revenue at ₹1.65L
- Wholesale segment generates **58.9% of total revenue**
  despite fewer customers
- **4 SKUs below reorder level** — inventory risk
  heading into peak season
- Necklaces lead category revenue at ₹0.4M+
- Delhi and Chennai are top revenue cities

---

## 🛠️ Tech Stack

| Tool | Usage |
|------|-------|
| Power BI Desktop | Report building, DAX, data model |
| Power Query | Data cleaning, type fixing |
| DAX | 15 KPI measures |
| Excel | Source dataset |
| Power BI Service | Publishing and sharing |

---

## 📐 Data Model

Star schema with Sales_Transactions as fact table:
- Sales_Transactions → Product_Master (Many to One)
- Sales_Transactions → Customers (Many to One)
- Sales_Transactions → Date_Table (Many to One)
- Date_Table marked as official date table

---

## 📸 Screenshots

### Executive Summary
![Executive Summary](screenshots/page1_executive_summary.png)

### Sales Analytics
![Sales Analytics](screenshots/page2_sales_analytics.png)

### Inventory Analytics
![Inventory Analytics](screenshots/page3_inventory_analytics.png)

### Business Insights
![Business Insights](screenshots/page4_business_insights.png)

---

## 💼 Resume Bullet

> Built 4-page Power BI dashboard analysing 560 
> transactions across 15 SKUs and 50 customers · 
> designed star schema data model · wrote 15 DAX 
> measures including MoM growth, inventory turnover, 
> gross margin % · identified wholesale segment drives 
> 58.9% of revenue · published to Power BI Service
