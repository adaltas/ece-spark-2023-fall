# Data Engineering with Spark

## Lab 1: Unstructured data analysis with RDDs

Analyze unstructured data (text) with RDDs and Spark Core Functions.

### Prerequisites

- Connect to the [Databricks Community Edition](https://community.cloud.databricks.com/login.html)
- Upload the provided notebook

### Goals

- Get familiar with the Databricks environment
- Get familiar with the most frequently used functions for RDD processing: `map`, `flatMap`, `reduceByKey`
- Learn how to define lambda functions
- Learn when you can use pure Python functionalities and constructs in Spark environment  

### Lab resources

- Notebook
- The text file is part of the Databricks workspace: `/databricks-datasets/SPARK_README.md`

### Useful links

- [RDD programming guide](https://spark.apache.org/docs/latest/rdd-programming-guide.html)
  - especially chapters `Transformations` and `Actions`  

### TO DO

Go through the notebook and follow the instructions in the cells:

1. Open the `SPARK_README` file and:
  - count the occurrence of each word
  - change all capital letters to lower case
  - remove stopwords
  - sort the words and their counts in alphabetical order
  - sort from most to least frequent word
  - remove punctuations
2. Look at the given code and try to understand what it does.
