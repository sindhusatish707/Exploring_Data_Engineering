# Exploring_Data_Engineering
<p>
  Taking 30 days to explore different aspects of data engineering and learning on the way.<br>
  Inspired by Machine Learning Community posts on LinkedIn by Tanishq Soni
</p>
<p>
  Day 1:<br>
  Knowledge Gain:<br>
  Data Engineering is a field that<br>
  1. collects raw data from APIs, sensors<br>
  2. saves data in data warehouses or data lakes<br>
  3. undergo some transformations like cleaning, structuring<br>
  4. deliver it to be used otherwise in machine learning models, dashboards
</p>
<p>
  Code:<br>
  Extracting data from an API, converting the json to DataFrame, select required columns and save it in a csv file.
</p>

<p>
  Day 2:<br>
  Knowledge Gain:<br>
  Difference between Data Engineer, Analyst and Scientist <br>
  1. Data Engineers collect and get data ready to be used<br>
  2. Data Analyst use clean data to analyse and gain valuable insights<br>
  3. Data Scientist adds some intelligence to the data
</p>
<p>
  Code:<br>
  Clean data, draw analysis and predict using Logistic Regression to predict for a value.
</p>

<p>
  Day 3:<br>
  Knowledge Gain:<br>
  Skills for a Data Engineering <br>
  1. SQL - query and manipulate data<br>
  2. Python - Scripting and automation<br>
  3. Linux and Shell - to work with servers and automation<br>
  4. Git - Version control<br>
  5. Cloud Platforms - new data pipelines<br>
  6. Workflow Orchestration - manage complex ETL jobs
</p>
<p>
  Code:<br>
  Create and load data to SQLite to simulate a mini warehouse and query the data.
</p>

<p>
  Day 4:<br>
  Knowledge Gain:<br>
  Different Data Storage Systems <br>
  1. Database - Store structural(SQL) or semi-structural(NoSQL) data. Useful for day to day operations (OLTP)<br>
  2. Data Warehouse - Store large volumes of structured data. Useful for BI dashboards. Optimised for analytics and reporting (OLAP)<br>
  3. Data Lake - Store raw, unstructured or semi-structured data. Requires some processing before using the data.
</p>
<p>
  Code:<br>
  Simulating a database and data warehouse using SQLite with some SQL query executions. Data Lakes are simulated by storing JSON data.
</p>

<p>
  Day 5:<br>
  Knowledge Gain:<br>
  Types of Data Processing <br>
  1. Batch Processing: Collected data is processed in bulk. Useful in historical analysis or scheduled jobs. <br>
  2. Stream Processing: Data is processed in real-time as it arrives. Useful in fraud detection and real-time dashboards.
</p>
<p>
  Code:<br>
  Use raw_data created to showcase batch processing by adding the amount and depict stream processing using for loop and adding to total as streamed.
</p>

<p>
  Day 6:<br>
  Knowledge Gain:<br>
  Moving and Transforming Data : ETL vs ELT <br>
  1. ETL (Extract -> Transform -> Load) - Extract data from source, transform by cleaning, structuring, and then load to warehouses where it will be stored. <br>
  2. ELT (Extract -> Load -> Transform) - Extract data and load into warehouse or lake where transformations are done using SQL. Commonly seen in cloud warehouses.
</p>
<p>
  Code:<br>
  Depicting the difference in operations in ETL and ELT pipelines on raw_data with pandas operations acting on it.
</p>
