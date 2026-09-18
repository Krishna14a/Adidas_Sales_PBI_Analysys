# Adidas_Sales_PBI_Analysys
# 👟 Adidas Sales Analysis – Power BI Dashboard

## 📊 Project Overview

This project is an **Adidas Sales Analysis Dashboard** developed using **Microsoft Power BI**.

The objective of this project is to analyze Adidas sales performance across different **regions, states, products, retailers, sales methods, and time periods**.

The dashboard converts raw sales data into interactive visual reports that help understand **sales trends, profitability, product performance, retailer performance, and geographical sales distribution**.

---

## 🎯 Project Objectives

* Analyze overall Adidas sales performance.
* Track total sales and total profit.
* Analyze total units sold.
* Calculate and monitor average price per unit.
* Analyze profit margin.
* Identify monthly sales trends.
* Compare sales performance across different regions.
* Analyze sales by U.S. states.
* Compare different Adidas products.
* Analyze sales performance by retailer.
* Compare different sales methods.
* Create an interactive dashboard using Power BI filters and slicers.

---

## 🛠️ Tools & Technologies

* **Power BI Desktop**
* **Power Query**
* **DAX**
* **Data Visualization**
* **Data Cleaning & Transformation**
* **Data Modeling**
* **Microsoft Excel / CSV Dataset**

---

## 📁 Dataset

The project uses Adidas sales transaction data containing information related to:

* Invoice Date
* Month
* Region
* State
* Product
* Retailer
* Sales Method
* Sales
* Profit
* Units Sold
* Price Per Unit
* Profit Margin

The dataset was transformed and prepared before creating the Power BI dashboard.

---

## 🔄 Data Preparation

The following steps were performed during the data preparation process:

1. Imported the Adidas sales dataset into Power BI.
2. Opened the data in **Power Query Editor**.
3. Checked and cleaned the dataset.
4. Prepared date-related fields for time-based analysis.
5. Prepared categorical fields such as Region, Product, Retailer and Sales Method.
6. Created calculated metrics using DAX.
7. Built the required data model.
8. Created interactive visuals and slicers.

---

## 📐 Key DAX Measures

The dashboard contains important business measures including:

### Total Sales

```DAX
Total Sales = SUM('Data Sales Adidas'[Total Sales])
```

### Total Profit

```DAX
Total Profit = SUM('Data Sales Adidas'[Total Profit])
```

### Total Units Sold

```DAX
Total Unit Sold = SUM('Data Sales Adidas'[Units Sold])
```

### Average Price Per Unit

```DAX
Avg Price Per Unit = AVERAGE('Data Sales Adidas'[Price per Unit])
```

### Average Profit Margin

```DAX
Avg Profit Margin = AVERAGE('Data Sales Adidas'[Profit Margin])
```

> Note: The exact column/measure names can vary depending on the final dataset/model. The measures above describe the business calculations used by the dashboard.

---

# 📊 Dashboard Features

## 1. KPI Cards

The dashboard provides important high-level KPIs:

* **Total Sales**
* **Total Profit**
* **Total Units Sold**
* **Average Price Per Unit**
* **Average Profit Margin**

These KPIs provide a quick overview of Adidas business performance.

---

## 2. Monthly Sales Trend

An **Area Chart** is used to analyze sales performance over time.

### Analysis

The chart uses:

* **X-axis:** Month
* **Y-axis:** Total Sales

This helps identify:

* Monthly sales trends
* High-sales periods
* Low-sales periods
* Changes in sales performance over time

---

## 3. Sales by State

A **Map / Shape Map** is used to visualize Adidas sales across different U.S. states.

### Analysis

The visualization helps identify geographical differences in sales performance.

It can be used to understand:

* States generating higher sales
* States generating lower sales
* Geographic sales distribution

---

## 4. Sales by Region

A **Donut Chart** is used to analyze sales contribution by region.

### Dimension

**Region**

### Measure

**Total Sales**

This allows comparison between different regions and shows how much each region contributes to overall sales.

---

## 5. Sales by Product

A **Clustered Bar Chart** is used to compare Adidas product performance.

### Dimension

**Product**

### Measure

**Total Sales**

This helps identify products with higher and lower sales performance.

---

## 6. Sales by Retailer

Another **Clustered Bar Chart** analyzes sales performance by retailer.

### Dimension

**Retailer**

### Measure

**Total Sales**

This provides a comparison of Adidas sales across different retail partners.

---

# 🎛️ Interactive Filters

The dashboard includes interactive slicers that allow users to dynamically filter the report.

### Available Filters

* **Sales Method**
* **Year**
* **Month**

Users can select different values and the dashboard visuals automatically update based on the selected filters.

---

# 📈 Business Insights

The dashboard can be used by business and sales teams to answer questions such as:

### Sales Performance

* What is the overall sales performance?
* How much total profit has been generated?
* How many units have been sold?
* What is the average selling price?

### Product Analysis

* Which Adidas products generate the most sales?
* Which products have lower sales?
* How does product performance change over time?

### Regional Analysis

* Which region contributes the most sales?
* Which states have stronger sales performance?
* Where are potential low-performing markets?

### Retailer Analysis

* Which retailers generate higher sales?
* How does sales performance vary between retailers?

### Sales Method Analysis

* How does sales performance differ between sales methods?
* What happens to the dashboard KPIs when a particular sales method is selected?

### Time Analysis

* How do sales change month by month?
* Which periods show higher or lower sales?

---

# 📊 Dashboard Visuals

| Visual              | Purpose                            |
| ------------------- | ---------------------------------- |
| KPI Cards           | Display important business metrics |
| Area Chart          | Analyze monthly sales trends       |
| Shape Map           | Analyze sales by state             |
| Donut Chart         | Analyze sales by region            |
| Clustered Bar Chart | Compare products                   |
| Clustered Bar Chart | Compare retailers                  |
| Sales Method Slicer | Filter sales by method             |
| Year Slicer         | Filter data by year                |
| Month Slicer        | Filter data by month               |

---

# 🧠 Skills Demonstrated

Through this project, I demonstrated practical knowledge of:

* Power BI Desktop
* Power Query
* Data Cleaning
* Data Transformation
* Data Modeling
* DAX Measures
* KPI Development
* Time-Based Analysis
* Geographic Analysis
* Product Analysis
* Retailer Analysis
* Interactive Slicers
* Business Intelligence
* Data Visualization
* Dashboard Development

---

# 🏗️ Project Workflow

```text
Raw Adidas Sales Data
        ↓
Data Import
        ↓
Power Query
        ↓
Data Cleaning & Transformation
        ↓
Data Modeling
        ↓
DAX Measures
        ↓
Interactive Visualizations
        ↓
Power BI Dashboard
        ↓
Business Insights
```

---

# 📌 Project Structure

```text
Adidas-Sales-PowerBI/
│
├── Adidas Sales Project.pbix
├── Dataset/
│   └── Adidas Sales Dataset.csv
│
├── Dashboard/
│   └── Adidas Sales Dashboard.png
│
└── README.md
```

---

# 🚀 Key Takeaway

This project demonstrates how **Power BI can transform raw Adidas sales data into an interactive business intelligence dashboard**.

The dashboard provides a consolidated view of **sales, profit, units sold, pricing, profit margin, product performance, retailer performance, regional performance, state-level sales, and monthly trends**.

It demonstrates an end-to-end Power BI workflow from **data preparation → transformation → DAX → visualization → business analysis**.

---

## 👨‍💻 Project Type

**Data Analytics | Business Intelligence | Power BI**

**Tool:** Microsoft Power BI
**Domain:** Sales & Retail Analytics
**Project:** Adidas Sales Analysis Dashboard
