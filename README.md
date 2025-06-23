# SSIS ETL Telecom Usecase


# Telecom ETL Project - SSIS Data Integration Solution

## Overview

This project demonstrates a complete ETL (Extract, Transform, Load) pipeline built with **Microsoft SSIS** to automate the integration of telecom customer transaction data into a structured SQL Server database.

The solution simulates a real-world use case where a telecom company generates CSV files every 5 minutes containing customer activity data. The ETL process handles data validation, rejection tracking, file management, and data quality reporting to ensure reliable and traceable data storage.

---

## Key Features

✅ Automated extraction of periodic CSV files
✅ Data validation and rejection handling for invalid records
✅ Storage of valid records into a SQL Server database
✅ Rejected records logged into a dedicated rejection table with source file reference
✅ Generation of key metrics:

* Total records per file
* Successfully stored records
* Rejected records count
  ✅ Archival of processed CSV files for traceability
  ✅ Utilization of Microsoft SSIS and SQL Server BI Stack

---

## Tools & Technologies

* **Microsoft SSIS (SQL Server Integration Services)**
* **SQL Server (SSMS, SSISDB)**



---

## Database Design

The database includes:
✔ **Transaction Table** – Stores valid customer transactions
✔ **Rejection Table** – Stores invalid records with source file reference
✔ **File Log Table** – Tracks record counts and rejection statistics for each processed file
