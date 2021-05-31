# Solving-data quality-issues-using-Pydeequ
Incoming data quality can make or break our application. Incorrect, missing, or malformed data can have a large impact on production systems. Examples of data quality issues include the following:
• Missing values can lead to failures in production system that require non-null values (NullPointerException)
• Changes in the distribution of data can lead to unexpected outputs of machine learning (ML) models
• Aggregations of incorrect data can lead to wrong business decisions
The challenges can be overcome by an effective technology pydeequ.
To understand and assert the quality of the data incoming from a data source in a ETL Pipeline we can further apply Pydeequ checks constraints to assert the data coming into pipeline on the data stored on AWS S3 of any file format specifically (csv,parquet) and storing the check details (SUCCESS/FAILURE) into AWS S3 and further perform neccessary actions on the data with FAILURE.

