# SQL and Data Warehouse Project

## Overview
This project demonstrates the design and implementation of an end-to-end Data Warehouse using SQL. It showcases how raw transactional data is transformed into structured, analysis-ready data using ETL (Extract, Transform, Load) processes.

The project is implemented using a Databricks notebook and follows industry-standard data warehousing practices including staging, transformation, and star schema modeling.


## Objectives
- Build a complete data pipeline using SQL
- Perform data cleaning and transformation
- Design a Data Warehouse architecture
- Implement Star Schema (Fact & Dimension Tables)
- Enable efficient data analysis and reporting


## Architecture
The project follows a layered architecture:

1. Raw Layer :– Contains original transactional data  
2. Staging Layer :– Stores raw data temporarily  
3. Transformation Layer :– Cleans and filters data  
4. Core Layer :– Stores processed and structured data  
5. Data Warehouse Layer :– Implements star schema  


## ETL Process
- Extract :- Data is loaded from raw tables  
- Transform :- Data is cleaned (e.g., removing null values)  
- Load :- Cleaned data is stored in core and warehouse tables  


## Data Model (Star Schema)

### Fact Table
- FACTSALES
  - OrderID
  - Customer Key
  - Product Key
  - Date Key
  - Region Key
  - Quantity
  - Unit Price
  - Total Amount

### Dimension Tables
- DIMCUSTOMERS :– Customer details  
- DIMPRODUCTS :– Product information  
- DIMDATE :– Date-related attributes  
- DIMREGION :– Geographic details  


## Technologies Used
- SQL  
- Databricks Community Edition  
- Data Warehousing Concepts  


## How to Run
1. Create a free account on Databricks Community Edition  
2. Upload the `.ipynb` file  
3. Run all cells sequentially  
4. Explore tables and queries  


## Key Learnings
- Understanding of ETL pipelines
- Hands-on experience with Data Warehouse design
- Implementation of Star Schema
- Writing optimized SQL queries  


## Future Enhancements
- Add dashboard using Power BI / Tableau  
- Automate ETL pipeline  
- Use real-world large datasets  


## Acknowledgement
This project was created as part of learning and hands-on practice in SQL and Data Warehousing concepts.
