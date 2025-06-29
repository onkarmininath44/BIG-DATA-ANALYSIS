# BIG-DATA-ANALYSIS
PERFORM ANALYSIS ON A LARGE DATASET USING TOOLS LIKE PYSPARK OR DASK TO DEMONSTRATE SCALABILITY.

*COMPANY*: CODTECH IT SOLUTIONS
*NAME*: ONKAR DEVAKR
*INTERN ID*: CT12DF308
*DOMAIN*: DATA ANALYTICS
*DURATION*: 12 WEEKS
*MENTOR*: NEELA SANTOSH KUMAR

# 📊 BigMart Sales Analysis using PySpark

This project performs big data analysis on the BigMart sales dataset using **PySpark**, focusing on large-scale data processing, cleaning, and deriving meaningful business insights.

---

## 📁 Dataset

**Source:** [BigMart Sales CSV](./BigMart%20Sales.csv)  
**Rows:** 8,523  
**Columns:** 12  
Includes data on item sales, item types, outlet types, MRP, and more.

---

## ⚙️ Tools & Technologies
- Python
- Apache **PySpark**
- Jupyter Notebook
- Pandas (for optional visualization)
- Matplotlib / Seaborn (optional)

---

## 🚀 Project Objectives

- Load and handle a large dataset using **PySpark**
- Perform **data cleaning** and **feature engineering**
- Analyze:
  - Sales by item types
  - Outlet type performance
  - Price range impact on sales
  - Trends by location and establishment year
- Demonstrate the **scalability** of PySpark for big data processing

---

## 🧠 Key Insights

- 🥤 *Soft Drinks* and *Snack Foods* have high sales volumes
- 🏬 *Supermarket Type1* outlets perform the best in total revenue
- 💰 High MRP items tend to generate more revenue
- 📍 Tier 3 locations and older outlets perform better in terms of sales

---

## 🧼 Data Cleaning

- Handled missing values in `Item_Weight` using **mean imputation**
- Filled missing `Outlet_Size` using the **mode**
- Standardized `Item_Fat_Content` categories

---

## 🔍 Analysis Conducted

- Top-selling `Item_Type` categories
- Revenue distribution across `Outlet_Type`
- Sales grouped by custom `MRP_Range` buckets
- Performance by `Outlet_Location_Type` and `Outlet_Establishment_Year`
- Focused insight: sales performance of **Soft Drinks** by outlet

---

## 📦 Project Structure

BigMart_PySpark_Analysis/
├── BigMart Sales.csv
├── BigMart_PySpark_Analysis.ipynb
├── README.md
└── (optional: output CSVs, plots)
