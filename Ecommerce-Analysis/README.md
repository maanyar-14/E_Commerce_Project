# E-Commerce Sales Analysis

## 📊 Project Overview

This project performs **E-Commerce Sales Data Analysis using Python**. The goal is to clean and analyze one year of sales transaction data and extract meaningful business insights related to revenue trends, customer ordering patterns, product performance, and peak ordering times.

The project uses **Pandas, NumPy, Matplotlib, and Seaborn** for data cleaning, exploratory data analysis, visualization, and business insight generation.

The dataset contains approximately **185,000+ sales transactions** from 12 months of e-commerce orders.

## 🎯 Objectives

* Clean and prepare the e-commerce sales dataset.
* Analyze monthly sales revenue.
* Identify the city with the highest number of orders.
* Find the best time of day for advertisements.
* Identify the top-performing products by revenue.
* Analyze the relationship between product price and quantity sold.
* Visualize important sales trends and patterns.
* Generate actionable business insights.

## 🛠️ Technologies Used

* **Python**
* **Pandas** – Data cleaning and analysis
* **NumPy** – Numerical operations
* **Matplotlib** – Data visualization
* **Seaborn** – Statistical visualization
* **Jupyter Notebook** – Interactive analysis

These are the main tools and libraries specified for the project.

## 📁 Project Structure

```text
Ecommerce-Analysis/
│
├── analysis.ipynb
│
├── data/
│   ├── Sales_January_2019.csv
│   ├── Sales_February_2019.csv
│   ├── ...
│   └── Sales_December_2019.csv
│
├── chart1_monthly_sales.png
├── chart2_city_orders.png
├── chart3_hourly_orders.png
├── chart4_top_products.png
├── chart5_category_heatmap.png
├── chart6_price_vs_quantity.png
│
└── README.md
```

## 🧹 Data Cleaning

The dataset was cleaned before analysis by:

* Removing completely empty rows.
* Removing repeated header rows.
* Removing remaining missing-value rows.
* Removing duplicate records.
* Converting `Quantity Ordered` to numeric format.
* Converting `Price Each` to numeric format.
* Converting `Order Date` to datetime format.

After cleaning, the dataset contained approximately **185,950 rows**.

## 🔧 Feature Engineering

The following new features were created:

* **Sales** – calculated using Quantity Ordered × Price Each
* **Month** – extracted from Order Date
* **Month Name** – readable month names
* **Hour** – extracted from Order Date
* **City** – extracted from Purchase Address
* **Category** – simplified product categories

## 📈 Analysis Performed

### 1. Monthly Sales Analysis

Monthly revenue was calculated using Pandas `groupby()` operations.

**December** recorded the highest monthly sales, with approximately **$4.61 million** in revenue.

### 2. City Order Analysis

Orders were grouped by city to identify locations with the highest order volume.

**San Francisco** recorded the highest number of orders in the provided analysis.

### 3. Peak Ordering Hours

Orders were analyzed by hour of the day to identify when customers were most active.

The analysis identified **7 PM** as the peak ordering hour, with **11 AM and 7 PM** highlighted as important advertising windows.

### 4. Top Products by Revenue

Products were ranked according to total revenue.

The **MacBook Pro Laptop** generated the highest revenue in the analysis, followed by products such as the iPhone and ThinkPad Laptop.

## 📊 Visualizations

The project includes six visualizations:

1. **Monthly Sales Revenue** – Bar and line chart showing monthly revenue and yearly trends.
2. **Orders by City** – Horizontal bar chart comparing order volumes across cities.
3. **Orders by Hour** – Visualization showing ordering activity throughout the day.
4. **Top 10 Products by Revenue** – Comparison of the highest-revenue products.
5. **Monthly Revenue by Category** – Seaborn heatmap showing category revenue across months.
6. **Price vs Quantity Sold** – Scatter plot showing the relationship between average product price and total units sold.

## 💡 Key Business Insights

Based on the analysis:

* **December** was the highest-revenue month.
* **San Francisco** had the highest order volume.
* **11 AM and 7 PM** were identified as important advertising periods.
* **MacBook Pro Laptop** generated the highest product revenue.
* Lower-priced products such as **USB-C Charging Cables** had high unit sales.
* Electronics contributed the largest share of revenue in the category analysis.
* The fourth quarter showed strong revenue performance.

## 💼 Business Recommendations

Based on the findings:

* Start holiday promotions before December.
* Bundle high-volume, lower-priced products with expensive electronics.
* Increase advertising during peak ordering periods.
* Consider increasing delivery capacity in high-order cities.

## ▶️ How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/deethyakj24ds-sketch/Ecommerce-Analysis.git
```

### 2. Install the required libraries

```bash
pip install pandas numpy matplotlib seaborn notebook
```

### 3. Open the project

```bash
cd Ecommerce-Analysis
jupyter notebook
```

### 4. Run `analysis.ipynb`

Run the notebook cells from top to bottom to reproduce the data cleaning, analysis, visualizations, and insights.

## 📌 Project Outcome

This project demonstrates practical skills in:

* Data cleaning
* Exploratory Data Analysis (EDA)
* Feature engineering
* Pandas GroupBy analysis
* Data visualization
* Business-oriented data interpretation
* Generating actionable insights from sales data

The project follows the required tasks of the **Data Analysis with Python – E-Commerce Sales Analysis** internship project.

## 👩‍💻 Author

**Deethya K J**

GitHub: [@deethyakj24ds-sketch](https://github.com/deethyakj24ds-sketch)

