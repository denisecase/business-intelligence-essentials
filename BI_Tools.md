# BI Tools

This page lists various tools used in Business Intelligence (BI). 
It categorizes tools based on their proprietary status, accessibility, and location. 

We start with the more accessible open source tools, but include proprietary offerings as well. 

-----

## Open Source Tools

We generally favor freely available, open source tools. 
Proprietary tools often perform the same or additional functions and can be even nicer to use. 
When we learn concepts with open-source tools, it makes it easier to learn the proprietary (more expensive, highly functional) options. 

### Apache Spark
An open-source unified analytics engine for large-scale data processing, featuring built-in modules for streaming, SQL, machine learning, and graph processing.

### Python
An open-source versatile programming language renowned for its ease of use and robust libraries in data analysis, machine learning, and automation.

### R
A software environment and programming language for statistical computing and graphics, widely used among statisticians and data miners.

## Proprietary Tools

### SAS
A comprehensive suite for advanced analytics, multivariate analyses, business intelligence, and data management.

### Tableau
Offers a leading platform for creating interactive and shareable dashboards, illustrating data patterns, trends, and insights. Available in a public version and offers 12-month academic trial licenses.

### Tableau Data Prep
Facilitates swift data cleaning, shaping, and combining with a direct and visual approach without coding. Available in a public version with academic licenses.

### Excel
Microsoft's spreadsheet software, widely used for data analysis and visualization with tools like pivot tables and formula functions.

### Power BI
Microsoft's business analytics service providing interactive visualizations and BI capabilities with a user-friendly interface.

### Looker
A Google Cloud data-discovery platform offering powerful analytics and insights through data exploration and interactive dashboards.

-----


## Tool Location

Cloud-based tools can be accessed via a modern web brower for convenient access. 
Locally installed tools allow us to work on local data without requiring an active internet connection. 

### Locally Installed (Private, Offline)

#### Visual Studio Code
A powerful, open-source editor that supports multiple programming languages and tools, widely used for developing applications including BI solutions.

#### Python
Often installed locally, Python allows developers to use libraries such as Pandas for data manipulation and PySpark for interacting with Apache Spark.

### Apache Spark
Apache Spark can be installed locally for practice. 
Spark is typically installed on a large number of computers called a cluster to process massive amounts of data concurrently.

### Cloud-based (Available via Web Browser)

#### Google BigQuery
A fully managed enterprise data warehouse on Google Cloud Platform, offering rapid SQL analytics and integrated machine learning capabilities. Offers a free tier.

#### Databricks
A proprietary platform established by the creators of Apache Spark, combining data engineering, science, analytics, and machine learning on a single unified platform.

-----

## Popular Data Manipulation Languages and Classes

It helps to know and understand these languages and classes when working with modern BI. 

### SQL (Structured Query Language)
An open-source standard programming language for managing and manipulating relational databases effectively.

### Pandas
A Python library for data manipulation and analysis, providing data structures and operations for manipulating numerical tables and time series.

### Polars
A DataFrame library written in Rust, focused on speed and efficiency, similar to Pandas but designed for performance.

### Spark DataFrame
Part of Apache Spark, provides a distributed collection of data organized into named columns, designed for large-scale data processing.

### Spark RDD (Resilient Distributed Dataset)
A basic data structure in Apache Spark.
RDDs excel at handling large amounts of data because they can divide their work across multiple machines (they are distributed). 
They automatically recover lost data (they are resilient).
They can't be changed (they are immutable).
They allow us to build new RDDs easily and control how we process data in detail. 
