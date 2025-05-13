# 🔥 PySpark Cheat Sheets

Comprehensive and practical cheat sheets for working with **PySpark**, including standard DataFrame operations, **Delta Lake on AWS**, **JSON transformation**, and **unstructured data parsing** with **Apache Tika**.

## 📘 Notebooks Included

### 1. [`PySpark_CheatSheet.ipynb`](./PySpark_CheatSheet.ipynb)
This notebook includes the **most common and essential PySpark commands**:
- SparkSession setup
- Reading and writing data (CSV, JSON, Parquet)
- DataFrame operations (select, filter, groupBy, withColumn)
- Aggregations, joins, window functions
- User-defined functions (UDFs)
- SQL queries on DataFrames
- Schema definition and type casting
- Performance tips (repartition, caching)

### 2. [`PySpark_Advanced_CheatSheet.ipynb`](./PySpark_Advanced_CheatSheet.ipynb)
This advanced cheat sheet covers:
#### 🔷 Delta Lake on AWS
- Read/write Delta tables to S3
- Upserts (MERGE), deletes, updates
- Time travel & versioning
- Optimize and VACUUM commands

#### 📄 Apache Tika (Unstructured Data)
- Parse PDFs, Word docs using Tika
- Extract and clean content for analysis
- Convert raw text into DataFrame
- Tokenization and cleanup

#### 🧾 JSON Parsing
- Load nested JSON from S3 or local
- Flatten nested fields
- Explode arrays
- Transform into tabular format

---

## 🧰 Requirements

To run the notebooks locally:

```bash
pip install pyspark tika
