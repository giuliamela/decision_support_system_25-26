# Business Intelligence System for Music Streaming

## Overview
This project implements an end-to-end Business Intelligence system for a music streaming platform, starting from heterogeneous data sources (JSON and XML) and building a complete analytical pipeline.

The system is designed to support data processing, storage, and analysis through a structured architecture, enabling advanced reporting and insights.

---

## Architecture

The project is organized into the following layers:

- Data Preparation (Python)  
  Data profiling, cleaning, and integration to transform raw data into structured formats.

- Data Warehouse (SQL Server)  
  Design and implementation of a snowflake schema, including fact tables, dimensions, and bridge tables.

- ETL Pipelines (SSIS)  
  Automated data extraction, transformation, and loading processes.

- OLAP Cube (SSAS)  
  Multidimensional model supporting analytical queries and hierarchical navigation.

- Visualization (Power BI)  
  Interactive dashboards built on top of the OLAP cube.

---

## Key Features

- End-to-end BI pipeline  
- Dimensional modeling (snowflake schema)  
- ETL automation with SSIS  
- Multidimensional analysis with SSAS and MDX  
- Integration with Power BI for data visualization  

---

## Technologies

- Python  
- SQL Server (T-SQL)  
- SSIS (ETL)  
- SSAS (OLAP)  
- MDX  
- Power BI  

---

## Repository Structure

- 00_data → Data at different stages of the pipeline  
- 01_src → Python scripts for data preparation  
- 02_sql → Data warehouse schema (T-SQL)  
- 03_ssis → ETL pipelines (SSIS project)  
- 04_mdx → OLAP cube and MDX queries  
- 05_dashboards → Power BI dashboards  

---

## Notes

This project was developed as part of my Master's degree in Data Science and Business Informatics at the University of Pisa.
