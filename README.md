# Data Warehouse SQL Project

Welcome to the **Data Warehouse SQL Project** repository! 🚀

This project demonstrates a complete data warehousing solution using SQL Server, from building a modern data warehouse to generating business-ready analytical datasets. It showcases industry best practices in data engineering, ETL, dimensional modeling, and SQL analytics.

---

# 🏗️ Data Architecture

The project follows the **Medallion Architecture** consisting of Bronze, Silver, and Gold layers.

- **Bronze Layer:** Stores raw ERP and CRM data imported from CSV files.
- **Silver Layer:** Cleans, validates, standardizes, and transforms the raw data.
- **Gold Layer:** Creates business-ready fact and dimension tables using a Star Schema for reporting and analytics.

---

# 📖 Project Overview

This project includes:

- **Data Architecture:** Designing a modern SQL Server Data Warehouse.
- **ETL Pipeline:** Extracting, transforming, and loading data into the warehouse.
- **Data Modeling:** Creating fact and dimension tables using a Star Schema.
- **Analytics & Reporting:** Writing SQL queries to generate business insights.

---

# 🎯 Skills Demonstrated

This project showcases practical experience in:

- SQL Development
- Data Warehousing
- Data Engineering
- ETL Pipeline Development
- Data Modeling
- Data Analytics

---

# 🛠️ Tools & Technologies

- Microsoft SQL Server
- SQL Server Management Studio (SSMS)
- T-SQL
- Git
- GitHub
- Draw.io

---

# 🚀 Project Requirements

## Building the Data Warehouse (Data Engineering)

### Objective

Develop a modern SQL Server data warehouse to consolidate business data for analytical reporting and decision-making.

### Specifications

- **Data Sources:** Import ERP and CRM datasets provided as CSV files.
- **Data Quality:** Clean and resolve data quality issues.
- **Integration:** Merge both datasets into a single analytical model.
- **Scope:** Load the latest dataset only.
- **Documentation:** Maintain clear documentation of the data model.

---

## BI Analytics & Reporting (Data Analytics)

### Objective

Develop SQL-based analytics to provide insights into:

- Customer Behavior
- Product Performance
- Sales Trends

These insights support data-driven business decisions.

---

# 📂 Repository Structure

```
Data_warehouse_sql/
│
├── dataset/                  # ERP & CRM datasets
│
├── Documents/                # Architecture and project documentation
│
├── script/
│   ├── bronze/               # Raw data loading scripts
│   ├── silver/               # Data cleaning & transformation
│   └── gold/                 # Star schema & analytical models
│
├── Test/                     # Validation & quality check scripts
│
├── README.md
├── LICENSE
└── .gitignore
```

---

# 📈 Future Improvements

- Incremental Data Loading
- SQL Agent Automation
- Power BI Dashboard Integration
- Performance Optimization
- Cloud Deployment (Azure)

---

# 🛡️ License

This project is licensed under the **MIT License**.

---

# 🙏 Acknowledgements

This project is inspired by the **SQL Data Warehouse Project** by **Data with Baraa** and has been recreated for learning, practice, and portfolio development.

---

## ⭐ Support

If you found this project useful, consider giving it a **⭐ Star** on GitHub.
