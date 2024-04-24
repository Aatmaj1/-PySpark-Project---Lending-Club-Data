# Lending Club Data Project Using PySpark

This repository contains Jupyter notebooks demonstrating the data cleaning and transformation process for a Lending Club dataset using PySpark. The project is designed to leverage the power of Apache Spark to process and clean large datasets efficiently.

## Overview of Notebooks

### LendingClub_Intro.ipynb: 
This introductory notebook provides an overview of the dataset and project objectives. It sets the stage for subsequent data cleaning and transformation tasks.

### LendingClub DataCleaning S1.ipynb: 
This notebook showcases various data cleaning steps, such as renaming columns, adding an ingestion date, removing duplicate rows, handling missing values, and cleaning specific columns like emp_length and address_state. It utilizes PySpark transformations like withColumn, dropDuplicates, and fillna to accomplish these tasks.

### LendingClub DataCleaning S2.ipynb: 
The second data cleaning notebook applies additional transformations, focusing on data type consistency, null value handling, and cleaning columns like loan_term_months and loans_purpose. PySpark functions like selectExpr, cast, and dropna are used for these operations.

### LendingClub DataCleaning S3.ipynb and S4.ipynb: 
These notebooks demonstrate further data cleaning and transformation processes using PySpark. Techniques like filter, groupBy, agg, and withColumnRenamed are employed to enhance data quality and structure.

## Key PySpark Features

1. Scalability and Performance: PySpark's distributed processing capability allows for efficient data transformation, even with large datasets.

2. Data Cleaning and Transformation: The project uses a range of PySpark functions and transformations to clean and preprocess the Lending Club data, including column renaming, data type conversion, handling null values, and duplicate removal.

3. Column-Level Operations: The notebooks demonstrate various column-level transformations using PySpark, such as modifying column names, adding new columns, and changing data types.

4. Advanced Transformations: The project uses advanced PySpark techniques like groupBy, agg, and filter to manipulate and aggregate data as needed.
