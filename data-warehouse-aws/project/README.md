# Project: Data Warehouse

This project builds an ELT pipeline that extracts data from S3, stages them in Redshift, and transforms data into a set of fact and dimensional tables for Sparkify analytics team to continue finding insights in what songs their users are listening to.

### etl.py
ELT pipeline builder

### create_tables.py
Creating staging, fact, and dimension table schema

### sql_queries.py
SQL query statement collecitons for create_tables.py and etl.py


## How to run? 
First run create_tables.py, and then run etl.py