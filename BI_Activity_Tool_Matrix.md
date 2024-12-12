# BI Activity Tool Matrix

The information provided is based on our understanding and evaluation of various BI tools. 
Descriptions are intended for educational discussion only - they are not official endorsements or representations by the respective companies. 
Please refer to the official websites of each tool for the most accurate and up-to-date information about each option. 

## Key Open Source Analysis Tools 

| BI Activities         | Apache Spark                              | Python                                 | SQL                                   | 
|-----------------------|-------------------------------------------|----------------------------------------|---------------------------------------|
| Data Collection       | Good (connects to various data sources)   | Excellent (libraries for scraping/APIs)| Excellent (query databases)          | 
| Data Cleaning         | Good (dataframes API for cleaning)        | Excellent (libraries like pandas)     | Good (SQL queries can perform tasks)  | 
| Data Transformation   | Excellent (scalable transformations)      | Excellent (pandas, NumPy)             | Excellent (complex queries)           |
| Data Analysis         | Excellent (large-scale analysis)          | Excellent (statistical libraries)     | Good (basic analytics)               | 
| Data Visualization    | Limited (basic plotting capabilities)     | Excellent (matplotlib, seaborn, etc.) | Limited (not designed for visualization)|
| Real-Time Processing  | Excellent (stream processing capabilities)| Good (with libraries like PySpark)    | Limited (not designed for real-time) | 
| Machine Learning      | Excellent (MLlib for scalable ML)         | Excellent (scikit-learn, TensorFlow)  | Limited (possible but impractical)   | 
| Scalability           | Excellent (big data and clusters)         | Good (with frameworks like Dask)      | Good (depends on database scalability)| 
| Ease of Use           | Moderate (requires big data expertise)    | Moderate (requires programming)       | Good (widely known syntax)           | 
| Integration           | Good (with big data tools)                | Excellent (most data sources supported)| Excellent (database standard)       | 
| Open Source/Free      | **Yes**                                       | **Yes**                                   | **Yes**                                   | 

## Selected Visualization Tools

| BI Activities         | Power BI                                | Tableau Prep + Tableau               | Metabase                              | Shiny                            |
|-----------------------|-----------------------------------------|--------------------------------------|---------------------------------------|-------------------------------------|
| Data Collection       | Good (connects to various sources)     | Good (integrates with databases/APIs)| Good (simplifies connections)        | Moderate (requires additional setups)|
| Data Cleaning         | Good (intuitive for beginners)         | Excellent (cleaning and reshaping)  | Moderate (basic cleaning features)   | Moderate (less intuitive)          |
| Data Transformation   | Excellent (robust for transformations) | Good (drag-and-drop interface)      | Moderate (custom queries supported)  | Moderate (more scripting required) |
| Data Analysis         | Excellent (built-in analytics)         | Good (strong visual focus)          | Good (interactive filtering)         | Good (customizable UI for analysis)|
| Data Visualization    | Excellent (interactive visualizations) | Excellent (designed for visuals)    | Good (clean, simple charts)          | Good (interactive dashboards)     |
| Real-Time Processing  | Good (real-time dashboards)            | Not applicable                      | Limited (basic real-time capabilities)| Limited (requires custom integrations)|
| Machine Learning      | Moderate (via integrations)            | Not applicable                      | Not applicable                       | Not applicable                     |
| Scalability           | Good (enterprise-ready)                | Good (scales within environment)    | Moderate (smaller-scale usage)       | Good (scales with server resources)|
| Ease of Use           | Excellent (user-friendly)              | Excellent (drag-and-drop interface) | Excellent (simple for non-technical users)| Moderate (requires scripting)      |
| Integration           | Excellent (Microsoft ecosystem)        | Good (integrates with Tableau Suite)| Good (API-based integrations)        | Good (with R and Python)           |
| Open Source/Free      | No (free tier available)               | No (academic trial available)       | **Yes**                             | **Yes** |

## Additional Proprietary Tools

| BI Activities         | Looker (Google)                         | SAS                                   | Oracle BI                             |
|-----------------------|-----------------------------------------|---------------------------------------|---------------------------------------|
| Data Collection       | Good (integrates with databases/APIs)  | Good (connects to multiple sources)  | Good (supports various sources)       |
| Data Cleaning         | Good (uses LookML for transformations) | Excellent (comprehensive tools)      | Excellent (ETL and cleaning features)|
| Data Transformation   | Good (robust with LookML)              | Excellent (advanced transformation capabilities) | Excellent (powerful ETL tools)      |
| Data Analysis         | Excellent (data exploration and BI)    | Excellent (statistical and predictive analytics)| Excellent (designed for large-scale analytics)|
| Data Visualization    | Excellent (clean and interactive)      | Good (visualizations are secondary)  | Good (basic visualizations)          |
| Real-Time Processing  | Moderate (real-time with integrations) | Limited (not focused on real-time)   | Limited (real-time features available but complex)|
| Machine Learning      | Moderate (requires external tools)     | Excellent (built-in statistical models)| Excellent (via integrations)         |
| Scalability           | Excellent (scales with modern tools)   | Excellent (enterprise-grade scaling) | Excellent (designed for enterprise)  |
| Ease of Use           | Excellent (user-friendly interface)    | Moderate (requires SAS knowledge)    | Moderate (complex for beginners)     |
| Integration           | Excellent (integrates with modern ecosystems)| Good (works with many tools)         | Excellent (seamless with Oracle stack)|
| Open Source/Free      | No (subscription-based)                | No (academic licenses available)     | No (licensed software)               |


## Short Introduction to the Tool

### [Apache Spark](https://spark.apache.org)  

Apache Spark is an open-source unified analytics engine for large-scale data processing with built-in modules for streaming, SQL, machine learning, and graph processing.
It excels in big data, real-time processing, and complex data transformations.
It is scalable, designed for high performance, and popular with data engineers and scientists.
Spark is designed for data too big to process efficiently on one machine. It is run on clusters of computers.
We can use it with SQL, Python, or other languages, and the Spark engine handles the distribution and replication needed to perform analytics safely in the cloud.

To try Spark locally, students working on Mac and Linux can follow the installation instructions. 
Windows students can install WSL  (Windows Subsystem for Linux) and the Ubuntu Linux Distribution and follow the instructions.

Versions mattter. Spark 3.5.3 requires JDK (Java Development Kit) version 8, 11, or 17 - it will not work with JDK 21. 

Watch for Spark 4.0 coming soon - there is a [preview release available](https://spark.apache.org/news/spark-4.0.0-preview2.html). It supports JDK 21 and 17 out of the box. 

### [Python](https://www.python.org) 

Python is a versatile, open-source programming language known for ease of use and libraries for data analysis, machine learning, and automation. 
Libraries such as Pandas, NumPy, and SciPy provide powerful and popular tools for data manipulation and analysis. 
Python is widely used in academia and industry due to its comprehensive ecosystem.

### [SQL](https://en.wikipedia.org/wiki/SQL) 

SQL (Structured Query Language) is an open-source standard programming language for managing and manipulating relational databases. 
It is essential for data extraction, transactional queries, and database management. 
SQL is widely known and used by data professionals for handling structured data.

### [Microsoft Power BI](https://powerbi.microsoft.com)

Known for its integration with other Microsoft services, Power BI is widely regarded as excellent for data transformation, analysis, and visualization. 
It is user-friendly, making it accessible for users without advanced programming skills. 
Its real-time processing capabilities and machine learning offerings may not be as robust as more specialized tools.

To get experience, students can try [Power BI Services](https://powerbi.microsoft.com/en-us/power-bi-service/) (no sharing or publishing capabilities in the free option).

In addition, students on Windows can download [Power BI Desktop](https://powerbi.microsoft.com/en-us/desktop/) (no sharing or publishing capabilities in the free option).


### [Tableau Data Prep & Tableau](https://www.tableau.com)

Tableau Data Prep facilitates data cleaning, shaping, and combining with a visual approach that doesn't require coding.
Tableau offers powerful visualization and analysis capabilities, designed for non-technical users with drag-and-drop functionality.
Both come with a renewable 12-month academic trial license for students and educators.
It is user-friendly and uses a graphical interface to prepare data for analysis and visualization.

To get experience, students can download [Tableau Prep for Students](https://www.tableau.com/academic/students) and [Tableau for Students](https://www.tableau.com/academic/students) for free with academic credentials.

### [Metabase](https://www.metabase.com)  

Metabase is a growing tool in this space, particularly popular among small to medium-sized businesses and organizations looking for simplicity, cost-effectiveness, and open-source solutions. 
It is not as widely adopted as industry giants like Tableau or Power BI, but has gained recognition
for its intuitive design and ability to make data easily accessible and understandable to a wide range of users across an organization, regardless of their technical expertise.

After we install Java to enable Apache Spark, students can try Metabase by installing the jar file. 
Mac and Linux work well. Windows students can install WSL and Ubuntu. 
Metabase works with JDK 21, 17, and 11. For now, we need to stay with JDK 17 to work with Spark 3.5.3.

### [Shiny](https://shiny.rstudio.com)  

Shiny is an open-source platform that enables the creation of interactive web applications for data visualization and analysis.
It is popular in academia and research due to its flexibility and ease of integration with R-based statistical and analytical workflows.
Shiny apps require knowledge of Python (or R) programming and are suited for small to medium-scale projects.
Shiny is customizable and supports real-time interactive dashboards for data that can be processed on a single machine.

### [Looker (Google)](https://looker.com)  

Now part of Google Cloud, Looker excels in data analysis and visualization and integrates seamlessly with various data sources, particularly in cloud environments.
Its machine learning capabilities may be more limited.
It is user-friendly and excels at real-time data analysis, with a focus on LookML for advanced data modeling.

### [Oracle BI](https://www.oracle.com/business-analytics/bi/)  

Part of a larger suite of enterprise solutions, Oracle BI is strong in data integration, transformation, and analysis, particularly within Oracle’s ecosystem.
Its apabilities are tailored to users within Oracle-focused environments.
Oracle BI is robust for large-scale enterprise needs, and may have a steeper learning curve for beginners.

### [SAS](https://www.sas.com)  

Known for its advanced analytics, SAS excels in data analysis and machine learning.
It offers robust data cleaning tools and excellent integration capabilities, particularly in industries that prioritize data security and complex analysis, such as healthcare and banking.
SAS is widely used for predictive analytics and statistical modeling and common in enterprise-scale projects.
