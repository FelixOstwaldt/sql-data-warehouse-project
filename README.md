# Data Warehouse and Analytics Projects

Welcome to the **Data Warehouse and Analytics Project** repository!

Here we build a modern data warehouse with SQL Server, including ETL processes, data modeling, and analytics.

It is for testing and exploring Data Warehouse architecture and a work in process.


---

This is done after the tutorial video [SQL DATA Warehouse from Scratch | Full Hands-On Data Engineering Project](https://www.youtube.com/watch?v=9GVqKuTVANE).

---

## Data Architecture

The Data Warehouse is build after the Bronze - Silver - Gold Architecture. Data ist extracted directly into the Bronze layer as a full load without transformations. From there the tables are transformed in the Silver layer. At the end in the Gold layer the tables are cponverted into views with data integration, aggregation and business logic. 

[](sql-data-warehouse-project/doc/data_architecture.png)
