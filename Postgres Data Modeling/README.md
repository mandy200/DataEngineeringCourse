# Sparkify Project

### I - Purpose

This project was aimed to provide the startup with a sipmle way to store and query their data.
It was previously stored inside json files. We provided them with SQL tables depicting data collected on users activity and songs.
They can now query their data in order to analyse it by operating SELECT queries.


### II - Database schema
My database schema is a star schema meaning all dimension tables are linked to the fact table. The fact table is songplays and the 4 other tables are dimension tables.
The ETL pipeline reads from Json files, then fetches desired data from it and pushes it into targeted table.

### What should I execute ?
Please note that source data is not inserted.
To ensure the code is functionnal you can execute:
1) sql_queries.py
2) create_tables.py
3) etl.py
4) test.ipynb


If you want to test the notebook, please re-run create_tables.py before executing etl.ipynb. 
You can then check data insertion by running test.ipnb


### How to run it ?
.py files -> open a terminal session and execute the following command: "python file_name.py"
Jupyter notebook files -> on each code cell: ctrl + enter