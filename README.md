
Lending Club Data Analysis
Problem Statement : To load the loan details dataset for 2018 Q4 of Lending Club and perform Data Cleaning. The prepared data would be used to perform EDA and Visualization to generate insights.

•	Loaded the dataset in Databricks using Pyspark.
•	Used pyspark functions like regex to clean the fields by extracting integers from values like “74.24%”, “< 1 year” etc, 
•	Removed null values from fields and filled them with average values using coalesce. Also performed some type casting
•	Added clean columns, removed extra columns and prepared the final table for further analysis and dash boarding
