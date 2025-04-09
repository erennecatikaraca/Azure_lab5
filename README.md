# Lab 5 - Analyze Files with Spark

This lab is part of the **Microsoft DP-203: Data Engineering on Microsoft Azure** training path. It focuses on analyzing structured CSV files using Apache Spark in Azure Synapse Analytics.

## 🚀 Objectives

- Load a CSV file from Azure Data Lake Storage
- Analyze data using Spark DataFrame API
- Perform SQL-style queries with Spark SQL
- Visualize results using built-in Synapse tools

## 📂 Dataset

The dataset used in this lab is `products.csv`, containing product data such as:

- Product names and IDs  
- Category and subcategory names  
- List prices and standard costs

## 🧪 Key Tasks

1. **Load CSV data** from Azure Data Lake into a Spark DataFrame  
2. Use `select()`, `filter()`, and `orderBy()` for data exploration  
3. Aggregate data with `groupBy()` and `avg()`, `count()` functions  
4. Register DataFrame as a temporary view and write **Spark SQL** queries  
5. Visualize results (bar charts, etc.) inside Synapse notebooks

## 🛠 Technologies Used

- Azure Synapse Analytics  
- Apache Spark (PySpark)  
- Azure Data Lake Storage  
- Spark SQL  
- Synapse Studio notebooks

## ✅ Outcomes

- Tabular data was queried and analyzed using Spark  
- Both the DataFrame API and Spark SQL were used for data analysis  
- Results were visualized within Azure Synapse