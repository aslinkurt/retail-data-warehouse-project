# Retail Data Warehouse Project

This project presents a comprehensive data management solution for a fictional Superstore using SQL. It includes the creation of a normalized relational database and a star schema data warehouse designed to support advanced retail analytics.

## 📌 Project Overview
- **Tools Used**: MySQL, Power BI, Lucidchart

## 🗃️ Dataset

- Sourced from: [Tableau Superstore Dataset](https://public.tableau.com)
- Records: 100 unique orders
- Format: CSV (`Only_unique_oder_id_100_rows_only.csv`)

## 🧱 Database Design

- **Normalization**: Achieved up to 3NF
- **SQL Schema Includes**:
  - Customer, Product, Geography, Segment, Ship Mode, Sales Rep
  - Orders and Order Details
  - Referential integrity enforced with primary and foreign keys

## ⭐ Data Warehouse Design

- **Star Schema** with:
  - Fact Tables: `FactSales`, `FactOrder`
  - Dimension Tables: `DimCustomer`, `DimProduct`, `DimGeography`, `DimTime`, `DimShipMode`, `DimSalesRep`

- **ETL Logic**:
  - Extracted from a transactional flat table
  - Transformed into normalized and star-schema-ready tables using SQL
  - Loaded with strict constraint validation

## 📊 Business Insights

Power BI dashboards and SQL queries answer key business questions:

- Total Sales by Category
- Top 5 Customers by Sales
- Sales Trends Over Time
- Sales Performance by Sales Representative

## 📁 Files

- `project.sql` – SQL scripts for schema creation, data transformation, and ETL
- `Only_unique_oder_id_100_rows_only.csv` – Source transactional dataset
- `GBA 6220 Data Management Project.docx` – Full documentation of project steps
- `GBA 6220 Project.pptx` – Final presentation slides

## 🚀 How to Run

1. Clone this repo:
   ```bash
   git clone https://github.com/aslinkurt/retail-data-warehouse-project.git

