# 3. Data Engineering for ML

> Russian version: [03_data.md](../ru/03_data.md)

> ML Engineers need data engineering skills to build real systems, not just notebooks.

---

## SQL advanced

- [ ] Joins: inner, left, full, cross, semi, anti
- [ ] Window functions: `ROW_NUMBER`, `LAG` / `LEAD`, `SUM() OVER`
- [ ] CTEs and recursive CTEs
- [ ] Subqueries, `EXISTS` vs `IN`
- [ ] Indexes, `EXPLAIN`, query optimization
- [ ] Partitioning, sharding
- [ ] PostgreSQL and ClickHouse

**Resources:**
- [Mode SQL Tutorial](https://mode.com/sql-tutorial/)
- [SQLBolt](https://sqlbolt.com/)
- [DataLemur](https://datalemur.com/)
- [ClickHouse docs](https://clickhouse.com/docs)

---

## Pandas, Polars, NumPy

- [ ] NumPy: vectorization, broadcasting, fancy indexing
- [ ] Pandas: groupby, merge, pivot, `apply` vs vectorization
- [ ] Memory optimization: `category`, smaller integer types
- [ ] Polars: lazy execution, faster dataframe workflows
- [ ] EDA: dataset profiles, missing values, anomalies

---

## Big data stack

- [ ] Apache Spark, PySpark
- [ ] DataFrame API and Spark SQL
- [ ] Partitioning, broadcast joins
- [ ] UDF and Pandas UDF
- [ ] Hadoop / HDFS basics
- [ ] Hive, Trino, Presto

---

## Orchestration and pipelines

- [ ] Apache Airflow: DAGs, operators, sensors, TaskFlow API
- [ ] XCom, branching, dynamic DAGs
- [ ] dbt for warehouse transformations
- [ ] Alternatives: Prefect, Dagster

---

## Streaming

- [ ] Apache Kafka: producers, consumers, topics, partitions
- [ ] Spark Streaming and Flink basics
- [ ] Online features and real-time inference use cases

---

## Storage

| Type | Tools | Where it appears |
|---|---|---|
| OLTP | PostgreSQL, MySQL | backend systems |
| OLAP | ClickHouse, Greenplum | analytics |
| DWH | Snowflake, BigQuery | cloud analytics |
| Data lake | S3 / HDFS + Parquet / Iceberg | large-scale ML |
| Vector DB | Qdrant, Milvus, Weaviate, pgvector | LLM / RAG |
| Feature store | Feast, custom platforms | production ML |

---

## Checkpoint project

Build an Airflow ETL pipeline:
1. Pull data from a public API, for example job vacancies.
2. Clean and enrich it with PySpark.
3. Load it into PostgreSQL and ClickHouse.
4. Build an analytics table for Superset or Metabase.
5. Run it with `docker-compose`.
