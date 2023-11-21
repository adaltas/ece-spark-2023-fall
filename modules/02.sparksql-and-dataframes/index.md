---
Duration: 3 hours
---

# SparkSQL & DataFrames

## RDDs: Pros and Cons

- Pros
    - Developers: **low level control** of execution
- Cons
  - For user
      - **complicated** to express complex ideas
      - **difficult** to understand the code
  - For Spark: lambda functions are **opaque** (no optimization)

## DataFrames

- Structured dataset:
  - In-memory, distributed tables
  - Named and typed columns: schema
  - Collection of **Row**s
- Sources available: structured files, Hive tables, RDBMS (MySQL, PostgreSQL, …), RDDs
- High-level APIs

## RDDs vs DataFrames: code

![RDDs vs DataFrames code](./image/rdd_dataframe_code.PNG)

## RDDs vs DataFrames: performance

![RDDs vs DataFrames performance](./image/rdd_df_performance.PNG)

### Catalyst optimizer

![Catalyst optimizer](./image/catalyst_optimizer.png)

## Working with DataFrames

Querying DataFrames:
- By **chaining** functions

```python
df
  .select(...)
  .filter(...)
```

- By writing **SQL strings**

```python
spark.sql("SELECT * FROM table")
```

## Why SQL?

- Around since the 70s
- Huge enterprise usage:
  - Lots of users
  - Lots of projects
- But: cannot be used for ML or graph analyses
