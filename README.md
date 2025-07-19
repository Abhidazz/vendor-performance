###  IF YOU WANT TO RUN THIS PROJECT, THE DM ME I WILL PROVIDE YOU ZIP FILE , ITS MORE THAN 100MB SO I AM NOT ABLE TO UPLOAD IT HERE  ###


# 📊 Vendor Performance Analysis

## 🧩 Business Problem
Retail and wholesale companies often suffer losses due to:
- Inefficient pricing
- Poor inventory turnover
- Vendor dependency

This project aims to **analyze vendor performance** to enhance profitability and optimize product pricing.

## 🎯 Objectives
- Identify underperforming but high-margin brands for promotion.
- Find top vendors driving sales and gross profit.
- Evaluate cost savings from bulk purchasing.
- Assess inventory turnover to reduce holding costs.
- Compare profit margins between high and low-performing vendors.

## 🛠️ Project Structure
- `Exploratory Data Analysis.ipynb`: Initial EDA to understand key performance indicators.
- `Vendor Performance Analysis.ipynb`: Final analysis to extract insights from sales and vendor data.
- `get_vendor_summary.py` & `ingestion_db.py`: Scripts to ingest and summarize data from the SQLite database.
- `inventory.db`: Contains the raw vendor, sales, and product data (excluded from repo if >100MB).
- `vendor_sales_summary.csv`: Exported final summarized data for visualization/reporting.
- `vendor_performance.pbix`: Power BI report for interactive dashboards.
- `Vendor Performance Report.pdf`: PDF summary of all insights.

## 📁 Data Note
Due to size limitations, `inventory.db` (2GB) is not included in the repository. Use the `vendor_sales_summary.csv` file as a sample to run the notebooks.

## 📈 Insights Highlight
- Discovered brands with **low sales but high profit margins** suitable for promotional efforts.
- Identified vendors with **high inventory turnover** and those lagging behind.
- Built a **comprehensive sales summary** using SQL joins across sales, vendors, and product tables.

## 📦 Requirements
- Python 3.x
- pandas, numpy, seaborn, matplotlib, sqlalchemy, sqlite3

---

> 🔍 For more info, see `Vendor Performance Report.pdf` in this repository.
