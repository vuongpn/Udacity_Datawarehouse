# Project Description:
This project is an implementation of a Data Warehouse and AWS RedShift. It contains the ETL pipeline that extracts data from S3, stages them in Redshift, and transforms data into a set of dimensional tables for their analytics team.The data on S3 contains song and log information from a music store. This solution enables music stores to easily process loads of information efficiently.

# ETL Pipeline:
1.Load song and log data both from S3 buckets.
2.Stage the loaded data.
3.Transform the data into the above described data schema.

# File in project:
dwh.cfg : contains config data
create_table.py: contains script to create and drop table
etl.py: contains script to insert and load table
sql_queries.py: contains queries to create, drop, copy and insert table

# Checkout my ceritificate:
https://confirm.udacity.com/NJDZKKZC
