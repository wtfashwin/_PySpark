# PySpark Learning Notebooks

A notebook collection for practicing Spark DataFrames, SQL, and common data transformations with PySpark.

## Topics

The numbered notebooks cover:

1. DataFrames and RDDs.
2. Aggregate functions.
3. Built-in functions.
4. DataFrame operations.
5. Reading, transforming, and writing JSON.
6. Spark SQL.
7. Date and timestamp functions.
8. Joins.
9. Set operators.
10. Pivot and unpivot operations.

## How to use it

Open the `.ipynb` files in a Python 3 notebook environment with PySpark and a Java runtime compatible with your chosen Spark version. Some examples also use pandas. The repository does not pin a Python, Java, Spark, or dependency version.

Start with `1_DataFrame_and_RDD.ipynb` and run the inline DataFrame examples one cell at a time. Before running file-loading cells, replace `/content/...`, `/home/...`, and `file_path` examples with paths to your own sample files. The referenced CSV and JSON inputs are not included in the repository. Check output paths too: some examples write files or overwrite an output directory.

## Status and checks

Learning notes and experiments. There is no application entry point or automated test suite. Saved outputs include Spark errors. A saved result is not proof of a clean run on another machine.

## Attribution and license

Some examples identify [SparkByExamples.com](https://sparkbyexamples.com/) in the notebook source. Retain the original example credits. No repository license file is included.
