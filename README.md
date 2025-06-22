# Home_Sales
This challenge focuses on using SparkSQL to analyze home sales data efficiently. The goal is to determine key metrics related to home prices based on various attributes, such as the number of bedrooms, bathrooms, and square footage. The purpose is to leverage big data tools for real estate insights, helping analysts and businesses make data-driven decisions about home pricing trends. 

### Key Steps:
1.	Data Processing – Load home sales data into a PySpark DataFrame and create a temporary table.
2.	Querying with SparkSQL – Compute average home prices based on different criteria, such as year built, number of bedrooms, and view rating.
3.	Performance Optimization – Cache and uncache tables to compare query runtimes.
4.	Partitioning Data – Organize data by build year to improve efficiency.
5.	Final Analysis & Upload – Verify caching behavior and upload results to GitHub.
