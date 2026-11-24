# BlinkIt-Outlet-Sales-Case-Study
An interactive Power BI dashboard analysing sales performance for **Blinkit** (India's last-minute delivery app) using grocery outlet and item-level data. It shows how sales vary across product categories, outlet sizes, locations and fat content.

## 📌 Overview

The dashboard is a single-page, Blinkit-themed report (green and white) with a left-hand branding panel, a row of headline KPIs and several breakdown charts. A **metric selector** lets the viewer switch the measure shown in the item type, fat content and outlet location charts.

## 📊 KPIs

| KPI | Description |
|---|---|
| **Total Sales** | Overall revenue across all outlets |
| **Average Sales** | Average sales per item/transaction |
| **No. of Items** | Total number of items sold |
| **Average Rating** | Mean customer rating |

## 📈 Visualisations

- **Sales by Outlet Establishment Year** (line chart): sales trend by the year outlets were established
- **Sales by Item Type** (bar chart): top- and bottom-performing product categories
- **Sales by Item Fat Content** (donut chart): Low Fat vs Regular split
- **Sales by Outlet Size** (donut chart): Small, Medium and High outlets
- **Sales by Outlet Location Tier** (funnel chart): Tier 1, 2 and 3 cities
- **Fat Content by Outlet Location Tier** (clustered bar chart): fat content mix within each city tier
- **Metric Slicer**: dynamically switches the measure across the charts

## 🛠️ Tools & Skills Used

- **Power BI Desktop**
- **DAX** (measures for Total Sales, Average Sales, No. of Items, Average Rating)
- **Power Query** for data cleaning and transformation
- Custom layout, background images and KPI card design

## 📂 Dataset

Blinkit Grocery Data, with fields including Item Type, Item Fat Content, Outlet Size, Outlet Location Type, Outlet Establishment Year, Sales and Rating.
<!-- Add the source link if public, e.g. Kaggle -->

## 🔍 Key Insights
<!-- Fill in from your own findings, for example: -->
- [Top-selling item category and its share of sales]
- [Which outlet size / location tier drives the most revenue]
- [Low Fat vs Regular contribution]
- [Sales trend across establishment years]

## 🚀 How to Use

1. Clone or download this repo.
2. Open `BlinkIt.pbix` in **Power BI Desktop**.
3. Use the metric slicer to switch measures and explore the charts.
