# Data Processing for big data with Apache Spark

## Background
The Department of Planning, Transport and Infrastructure (​DPTI​), South Australia collects data from various road crashes for further analysis in an endeavor to improve road safety. Over time, the data increases in size; the increase in the number of vehicles also contributes to huge amounts of data. As we look across multiple states, we can imagine a rather large set of data. Here, we want to employ various operations on the dataset using Spark to answer different queries.

**Required Datasets:**
- Two datasets (Unit and Crash datasets from year 2015-2019)
- A Metadata file is included which contains the information about the dataset.

## Information on Dataset
The data used here is the Road Crash Data from 2015-2019 for South Australia prepared by the Department of Planning, Transport and Infrastructure (​DPTI​) . The data is available on the website ​https://data.sa.gov.au​.

The datasets contain various details about the crash events including the vehicle and the people involved in the crash. In this assignment, only two datasets i.e. Crash and Units are considered. For more detailed information on the dataset, ​please refer to the Metadata file included in the assignment dataset or from the given website​.

**Note:** In the dataset, the exact day of the crash is not released by the data provider, being considered as sensitive information. When displaying dates, please use the format (​Year-Month-Dayofweek​) E.g. (2017-January-Sunday).

## Instructions
In this project, you are required to implement various solutions based on RDDs and DataFrames in PySpark for the given queries related to crash data analysis.

### 1. Working with RDD
In this section, you will need to create RDDs from the given datasets, perform partitioning in these RDDs and use various RDD operations to answer the queries for crash analysis.

### 2. Working with DataFrames
In this section, you will need to load the given datasets into PySpark DataFrames and use DataFrame functions​ to answer the queries.
Besides, compare and discuss the performance difference of these 3 approaches (RDDs vs DataFrame vs Spark SQL)
