# Shopify Stock Analysis Dashboard – README

## 📊 Project Overview

**Shopify Stock Analysis Dashboard** is an interactive **Power BI dashboard** created to analyze Shopify stock market data from **2017 to 2025**.

The dashboard provides an overview of stock prices and trading volume using KPI cards, date filters, metric selection, and a time-series chart.

## 🎯 Objectives

* Analyze Shopify stock market data.
* Monitor average stock prices.
* Analyze trading volume over time.
* Compare different stock metrics.
* Provide interactive date-based analysis.
* Visualize long-term stock trends from 2017 to 2025.

## 🛠️ Tools & Technologies

* **Microsoft Power BI**
* **Power Query** – Data cleaning and transformation
* **DAX** – Measures and calculations
* **Shopify Stock Dataset**
* **Data Visualization**

## 📌 Dashboard Features

### 1. KPI Cards

The dashboard displays the following key metrics:

* **Average of Close** – 57.41
* **Average of High** – 58.65
* **Average of Low** – 56.10
* **Average of Open** – 57.42
* **Average of Volume** – 18.47M

These cards provide a quick summary of the selected stock data.

### 2. Year Filter

A year-range slider is available to select the required period.

The dashboard currently covers data from approximately:

**2017 → 2025**

Users can adjust the range to analyze a specific period.

### 3. Metric Selection

The dashboard provides a metric selector with options such as:

* **20-Day MA**
* **50-Day MA**
* **Close Price**
* **Volume**

This allows users to change the metric displayed in the visualization.

### 4. Stock Volume Chart

The main chart displays **Average of Volume and Selection Metric by Date**.

It helps visualize changes in Shopify's trading volume over time and identify periods with higher or lower trading activity.

## 📈 DAX Measures

The dashboard contains calculated fields/measures such as:

* **20-Day MA**
* **50-Day MA**
* **Selection Metric**
* **Metric Value**

These measures allow the dashboard to dynamically display different stock metrics.

## 📂 Data Fields

The `shopify_stock` table contains stock-related fields such as:

* Date
* Open
* High
* Low
* Close
* Adjusted Close
* Volume

A separate **Date Table** is used for time-based analysis.

## 🔄 Dashboard Workflow

```text
Shopify Stock Dataset
        ↓
Data Cleaning & Transformation
        ↓
Create Date Table
        ↓
Create DAX Measures
        ↓
Create Metric Selection
        ↓
Build KPI Cards
        ↓
Create Time-Series Visualization
        ↓
Add Year & Metric Filters
        ↓
Shopify Stock Analysis Dashboard
```

## 💡 Key Insights

The dashboard can be used to:

* Monitor average opening and closing prices.
* Compare high and low stock prices.
* Analyze Shopify trading volume.
* Study stock activity across different years.
* View moving averages such as 20-Day and 50-Day MA.
* Dynamically switch between different stock metrics.

## 🚀 How to Use

1. Open the Power BI `.pbix` file.
2. Refresh the data if required.
3. Use the **Year slider** to select a time period.
4. Select a metric from the **Metric** options.
5. View the KPI cards for the selected data.
6. Analyze the chart to understand stock volume and metric trends.

## 📷 Dashboard Components

The dashboard contains:

* **5 KPI Cards**
* **Year Range Slider**
* **Metric Selection**
* **Time-Series Chart**
* **Date Table**
* **DAX Measures**
* **Interactive Power BI visuals**
