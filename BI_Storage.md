# BI Storage Solutions

This page explains data storage systems where BI data is kept, managed, and analyzed. 
Understanding these terms helps understand how data flows within BI systems and how various commonly accessible tools can be used with them.

## Data Warehouse

Centralized repositories that integrate data from multiple sources, structured in a format to support decision making, reporting, and analysis. 
Data warehouses are optimized for speed and efficiency in querying and reporting, rather than for the volume of data that can be stored.

- **Tableau Data Prep** is used to clean and transform data before loading into a data warehouse.
- **SQL** is used to query and manage data within a data warehouse. SQL is good for handling structured data and performing complex queries efficiently.

## Data Lake

A storage repository that holds a large amount of raw data in its native format until needed. 
Data lakes allow for big data and are capable of handling massive scale analytics. 
They are good for storing non-relational data and data without a predefined schema.

- **Python** is used to process and analyze data stored in data lakes due to its powerful libraries (e.g., Pandas for data manipulation and PySpark for handling big data).
- **Spark** is used for big data processing tasks in data lakes as it can handle large volumes of data and complex computations distributed across many computer clusters.

## Data Lakehouse

A hybrid data management architecture that combines the flexibility of data lakes with the management features of data warehouses. 
Data lakehouses support both BI and machine learning with a single source of truth. 
They are designed to provide the scalability of data lakes with the data management and ACID (Atomicity, Consistency, Isolation, Durability) capabilities of data warehouses.

- **Tableau Data Prep and SQL** are useful during the initial stages of data integration and transformation within a lakehouse setup, preparing data for advanced analytics with Spark.
- **Spark** integrates with data lakehouse architectures to provide advanced data processing capabilities, supporting data management tasks and complex analytical computations.

## Selecting Storage Solutions

Each type has unique characteristics that make it suitable for different types of data and usage scenarios.

- **Data Warehouses**: Integrity of data and fast querying capabilities.
- **Data Lakes**: Massive volumes of diverse data types and formats, stored cheaply.
- **Data Lakehouses**: Enable complex analytics and machine learning on large datasets without sacrificing the governance features of traditional data warehouses.

## Examples

### Data Warehouses
- Amazon Redshift
- Google BigQuery
- Snowflake

### Data Lakes
- Amazon S3
- Microsoft Azure Data Lake Storage
- Google Cloud Storage

### Data Lakehouses
- Databricks Lakehouse
- Amazon Redshift Spectrum
- Snowflake’s Hybrid architecture
