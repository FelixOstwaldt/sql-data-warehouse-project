# Data Warehouse and Analytics Projects

Welcome to the **Data Warehouse and Analytics Project** repository!

Here we build a modern data warehouse with SQL Server, including ETL processes, data modeling, and analytics.

It is for testing and exploring Data Warehouse architecture and a work in process.


---

This is done after the tutorial video [SQL DATA Warehouse from Scratch | Full Hands-On Data Engineering Project](https://www.youtube.com/watch?v=9GVqKuTVANE).

---

## Data Architecture

The Data Warehouse is build after the Bronze - Silver - Gold Architecture. Data ist extracted directly into the Bronze layer as a full load without transformations. From there the tables are transformed in the Silver layer. At the end in the Gold layer the tables are cponverted into views with data integration, aggregation and business logic. 

![Data_integration](/doc/data_architecture.png)

## Data Flow

Data flows only in one direction, form the source to Bronze, Silver and then Gold layer. Data is transformed in the Silver layer, but the tables are not changed. In the Gold layer the data is aggregated to make it more end-user friendly.

![Data_Flow](/doc/data_flow.png)

## Data Integration



![Data_integration](/doc/data_integration.png)

## Star Schema

![sales_data_mart](/doc/sales_data_mart.png)

## Data Catalog

The data catalog is found in the doc folder [here](/doc/data_catalog.md)
