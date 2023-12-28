# dbt-experiments

# dbt (Data Build Tool) has emerged as the poster child of “T” in ELT. It doesn’t do “E” or “L”, but just the “T”. Here’s how it works:

1. You can either use dbt Core (free) or dbt Cloud (paid) to create a new dbt project.
2. In the project, you specify your target data store credentials (e.g., Databricks, Redshift, Snowflake).
3. You then specify your transformations in SQL e.g., join sales table with customers and product, aggregate sales table over different geographies.
4. You then run your dbt project and it would create the target tables in your target data store.

![image](https://github.com/anjijava16/dbt-experiments/assets/5849522/ec51de20-1ad3-4641-94a9-4d354cc55ee6)

Ref Link: https://github.com/rxhl/dbt-databricks/tree/master
