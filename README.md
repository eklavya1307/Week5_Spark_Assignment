# Week 5 Spark Assignment

## Overview

This project demonstrates the use of Apache Spark DataFrames for data cleaning, transformation, filtering, aggregation, schema modification, and complete data processing pipelines.

The assignment focuses on understanding Spark fundamentals and implementing practical DataFrame operations using the Sample Superstore dataset.

---

## Objective

The objective of this assignment is to:

* Understand Spark fundamentals and DataFrame concepts
* Learn the limitations of MapReduce and advantages of Spark
* Perform data cleaning operations
* Handle null and inconsistent data
* Apply filtering conditions
* Perform aggregations using Spark functions
* Understand DataFrame immutability
* Understand shuffle operations and wide transformations
* Modify DataFrame schemas
* Build a complete data processing pipeline

---

## Dataset Used

**Dataset:** Sample - Superstore Dataset

The dataset contains sales and order information including:

* Order Details
* Customer Information
* Product Categories
* Sales and Profit Data
* Regional Information
* Shipping Details

---

## Technologies Used

* Python
* Apache Spark (PySpark)
* Jupyter Notebook
* VS Code
* GitHub

---

## Project Structure

```text
Week5_Spark_Assignment/
│
├── Sample - Superstore.csv
│
├── 01_Spark_Data_Cleaning_Transformation_Aggregation.ipynb
├── 02_Spark_Questions_Q1_Q15.ipynb
│
├── outputs/
│   └── final_pipeline_result.csv
│
├── screenshots/
│   ├── dataset_loaded.png
│   ├── schema_output.png
│   ├── data_cleaning.png
│   ├── filtering_output.png
│   ├── aggregation_output.png
│   ├── groupby_output.png
│   └── pipeline_output.png
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

## Notebook 1: Spark Data Cleaning, Transformation and Aggregation

This notebook demonstrates the practical implementation of Spark DataFrame operations.

### Topics Covered

* Spark Session Creation
* Dataset Loading
* Dataset Schema Analysis
* Spark DataFrame Concepts
* DataFrame Immutability
* Removing Duplicate Records
* Handling Null Values
* Schema Modification
* Type Casting
* Filtering Operations
* Aggregation Functions
* GroupBy Operations
* Shuffle and Wide Transformations
* Handling Inconsistent Data
* Complete Data Processing Pipeline
* Insights and Conclusion

---

## Notebook 2: Spark Questions (Q1–Q15)

This notebook contains solutions to all Week 5 Spark assignment questions.

### Concepts Covered

* MapReduce vs Spark
* In-Memory Computing
* Data Cleaning
* Null Value Handling
* Filtering Operations
* Aggregations
* GroupBy Operations
* DataFrame Immutability
* Schema Modification
* Shuffle Operations
* Wide Transformations
* Complete Processing Pipeline

---

## Key Spark Operations Implemented

### Data Cleaning

* Removed duplicate records using `dropDuplicates()`
* Handled missing values using `na.fill()`

### Data Transformation

* Modified schema using type casting
* Converted columns to appropriate data types

### Filtering

* Filtered records using single and multiple conditions
* Applied region and category-based filtering

### Aggregations

* Count
* Sum
* Average
* Minimum
* Maximum

### GroupBy Analysis

* Category-wise sales analysis
* Region-wise revenue analysis

### Processing Pipeline

A complete Spark pipeline was built by combining:

1. Duplicate Removal
2. Null Value Handling
3. Data Transformation
4. Aggregation
5. GroupBy Analysis

---

## Output

The final processed output is available in:

```text
outputs/final_pipeline_result.csv
```

This file contains the aggregated revenue and average sales generated from the complete Spark data processing pipeline.

---

## Screenshots

Project execution screenshots are available in the `screenshots` folder and include:

* Dataset Loading
* Schema Output
* Data Cleaning
* Filtering Operations
* Aggregation Results
* GroupBy Analysis
* Final Pipeline Output

---

## Key Learnings

Through this assignment, the following concepts were learned:

* Apache Spark Fundamentals
* Spark DataFrames
* In-Memory Processing
* Data Cleaning Techniques
* Data Transformations
* Aggregation Operations
* GroupBy Operations
* DataFrame Immutability
* Shuffle and Wide Transformations
* Building End-to-End Data Pipelines

---

## Conclusion

This assignment successfully demonstrates how Apache Spark DataFrames can be used to clean, transform, and analyze large datasets efficiently. By leveraging Spark's in-memory processing capabilities, complex data operations can be performed faster and more effectively compared to traditional disk-based approaches.
