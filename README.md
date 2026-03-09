# SQL Data Warehouse Project

> 📌 Built for learning purposes by following the DataWithBaraa SQL Data Warehouse tutorial.

---

## 🏗️ Architecture
```
Source Data → Bronze (Raw) → Silver (Cleaned) → Gold (Business-Ready)
```

- **Bronze Layer** — Raw ingestion from source systems, no transformation
- **Silver Layer** — Cleaned, standardized, and deduplicated data
- **Gold Layer** — Star schema (fact & dimension tables) optimized for reporting

---

## ✨ Key Features

- Full ETL pipeline using T-SQL stored procedures
- Incremental and full-load ingestion patterns
- Data quality checks and validation scripts
- Star schema data model ready for BI tools (Power BI, SSRS)

---

## 🗂️ Data Model

| Layer  | Objects              | Description                        |
|--------|----------------------|------------------------------------|
| Bronze | Raw tables           | Direct source data, no changes     |
| Silver | Staging/clean tables | Transformed and validated data     |
| Gold   | Fact & Dim tables    | Business logic, ready for analysis |

---

## ⚙️ Setup Instructions

1. **Requirements** — SQL Server 2019+ / SSMS
2. **Run DDL scripts** — Execute `/scripts/ddl/` to create databases and schemas
3. **Load Bronze** — Run `/scripts/bronze/load_bronze.sql`
4. **Transform to Silver** — Run `/scripts/silver/load_silver.sql`
5. **Build Gold layer** — Run `/scripts/gold/load_gold.sql`

---

## 📁 Project Structure
```
├── datasets/          # Source CSV files
├── scripts/
│   ├── bronze/        # Raw ingestion scripts
│   ├── silver/        # Cleaning & transformation
│   └── gold/          # Star schema & reporting views
└── docs/              # Architecture diagrams
```

---

## 🙏 Credits

This project was built by following the tutorial by [DataWithBaraa](https://github.com/DataWithBaraa/sql-data-warehouse-project). All credit for the architecture and design goes to the original author.
