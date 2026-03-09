# Data Warehouse and Analytics Project

> 📌 Built for learning purposes by following the [DataWithBaraa](https://github.com/DataWithBaraa/sql-data-warehouse-project) SQL Data Warehouse tutorial.

---

## 🏗️ Data Architecture

This project follows the Medallion Architecture with **Bronze**, **Silver**, and **Gold** layers:

- **Bronze Layer** — Raw data ingested as-is from CSV source files into SQL Server.
- **Silver Layer** — Data cleansing, standardization, and normalization.
- **Gold Layer** — Business-ready star schema optimized for reporting and analytics.

---

## 📖 Project Overview

1. **Data Architecture** — Modern Data Warehouse using Medallion Architecture.
2. **ETL Pipelines** — Extracting, transforming, and loading data from source systems.
3. **Data Modeling** — Fact and dimension tables optimized for analytical queries.
4. **Analytics & Reporting** — SQL-based reports for actionable business insights.

---

## 🚀 Project Requirements

### Data Engineering

**Objective:** Develop a modern data warehouse using SQL Server to consolidate sales data, enabling analytical reporting and informed decision-making.

**Specifications:**
- **Data Sources** — Import data from two source systems (ERP and CRM) provided as CSV files.
- **Data Quality** — Cleanse and resolve data quality issues prior to analysis.
- **Integration** — Combine both sources into a single, user-friendly data model.
- **Scope** — Focus on the latest dataset only; historization is not required.
- **Documentation** — Document the data model for both business and analytics teams.

### Data Analysis

**Objective:** Develop SQL-based analytics to deliver insights into:
- Customer Behavior
- Product Performance
- Sales Trends

---

## 📂 Repository Structure
```
data-warehouse-project/
├── datasets/        # Raw ERP and CRM CSV files
├── docs/            # Architecture diagrams and data catalog
├── scripts/
│   ├── bronze/      # Raw data extraction and loading
│   ├── silver/      # Cleaning and transformation
│   └── gold/        # Analytical models (star schema)
├── tests/           # Quality and test scripts
└── README.md
```

---

## 🛠️ Tools Used

- **SQL Server Express** — Database hosting
- **SSMS** — Database management GUI
- **DrawIO** — Architecture and data flow diagrams
- **Git & GitHub** — Version control

---

## 🙏 Credits

This project was built by following the tutorial by [DataWithBaraa](https://github.com/DataWithBaraa/sql-data-warehouse-project). All credit for the architecture and design goes to the original author.

## 🛡️ License

This project is licensed under the [MIT License](LICENSE).
