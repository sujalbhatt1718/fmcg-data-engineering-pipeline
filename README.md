# 🚀FMCG Data Engineering Pipeline

An end-to-end Data Engineering project built using **Databricks**, **PySpark**, **Delta Lake**, and **SQL** to process, transform, and analyze FMCG (Fast-Moving Consumer Goods) sales data. The project follows the **Medallion Architecture (Bronze → Silver → Gold)** to deliver clean, analytics-ready datasets and an interactive business dashboard.

---

## 📖 Project Overview

This project demonstrates a complete Data Engineering workflow, from raw data ingestion to business intelligence reporting.

The pipeline performs:

- Data ingestion into Databricks
- Data cleaning and transformation using PySpark
- Dimension and Fact table creation
- Data validation and quality checks
- Business analytics using SQL
- Interactive dashboard for business insights

---

## 🛠 Tech Stack

- Databricks
- Apache Spark (PySpark)
- Delta Lake
- SQL
- Python
- ETL Pipeline
- Data Warehouse
- Power BI / Databricks Dashboard
- Git & GitHub

---

## 📂 Project Structure

```
fmcg-data-engineering-pipeline/
│
├── 1_setup/
├── 2_dimension_data_processing/
├── fact_table/
├── Dashboard/
└── README.md
```

---

## 🏗 Architecture

```
                Raw CSV Files
                      │
                      ▼
              Bronze Layer
          (Data Ingestion)
                      │
                      ▼
              Silver Layer
    (Cleaning & Transformation)
                      │
                      ▼
               Gold Layer
      (Fact & Dimension Tables)
                      │
                      ▼
          SQL Analytics & Dashboard
```

---

## 📊 Dashboard Features

The dashboard provides real-time business insights including:

- 💰 Total Revenue
- 📦 Total Quantity Sold
- 👥 Unique Customers
- 💵 Average Selling Price
- 🛒 Top Products by Revenue
- 📈 Monthly Revenue Trend
- 🏪 Revenue Share by Sales Channel
- 👤 Top Customers by Revenue
- 📊 Product Price vs Quantity Analysis

---

## ⭐ Key Features

- End-to-End ETL Pipeline
- Medallion Architecture
- Delta Lake Storage
- Data Cleaning & Validation
- Dimension Table Processing
- Fact Table Generation
- Business KPI Reporting
- Interactive Dashboard
- SQL-Based Analytics
- Scalable Data Pipeline

---

## 📊 Data Model

### Dimension Tables

- Customer
- Product
- Store
- Supplier
- Date

### Fact Table

- Sales Fact

---

## 🎯 Business KPIs

- Revenue Analysis
- Customer Analysis
- Product Performance
- Sales Channel Performance
- Monthly Sales Trend
- Quantity Sold
- Average Selling Price
- Top Performing Customers

---

## 💡 Skills Demonstrated

- Data Engineering
- PySpark
- SQL
- ETL Development
- Delta Lake
- Databricks
- Data Warehousing
- Data Modeling
- Dashboard Development
- Business Analytics

---

## 🚀 Future Improvements

- Incremental Data Loading
- Streaming Data Pipeline
- Workflow Automation using Databricks Jobs
- CI/CD Integration
- Data Quality Monitoring
- Sales Forecasting using Machine Learning

---

## 📷 Dashboard

<img src="Dashboard/fmcg_dashboard.png" width="1000"/>

---

## 👨‍💻 Author

**Sujal Bhatt**

B.Tech – Computer Science & Business Systems

Data Engineering | Machine Learning | Python | SQL | Databricks

GitHub: https://github.com/sujalbhatt1718

LinkedIn: *Add your LinkedIn Profile*

---

⭐ If you found this project useful, don't forget to star the repository!
