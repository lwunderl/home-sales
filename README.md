# home-sales

* This jupyter notebook creates a spark session of home_sales from an S3 bucket and uses SQL to return queries in pyspark.
* The spark table is then cached and the query is timed to compare runtime to the uncached table.
* The table is then partitioned by date_built as a set of parquet files and the query is timed to compare runtime.