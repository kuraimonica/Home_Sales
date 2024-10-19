# Home_Sales
Module 22 Challenge
My code is in the Home_Sales.ipynb file and I used Google Colab to create and run my code.

I took the below steps to do my assignment:

I Imported the necessary PySpark SQL functions for this assignment, including queries to install Spark and Java on Google colab andsetting up the Environement variables.
I read the home_sales_revised.csv data in the starter code into a Spark DataFrame.
I created a temporary table called home_sales.

The following questions were answered using SparkSQL:
1) What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places.
2) What is the average price of a home for each year the home was built, that has three bedrooms and three bathrooms? Round off your answer to two decimal places.
3) What is the average price of a home for each year the home was built, that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? Round off your answer to two decimal places.
4) What is the average price of a home per "view" rating having an average home price greater than or equal to $350,000? Determine the run time for this query, and round off your answer to two decimal places.

I wrote a code to Cache my temporary table home_sales.
I checked if my temporary table is cached.
Using the cached data, I ran the last query that calculates the average price of a home per "view" rating having an average home price greater than or equal to $350,000. I determined the runtime and compared it to uncached runtime.

I partitioned by the "date_built" field on the formatted parquet home sales data.
I created a temporary table for the parquet data.
I ran the last query that calculates the average price of a home per "view" rating having an average home price greater than or equal to $350,000. I determined the runtime and compared it to uncached runtime.
I Uncache the home_sales temporary table.
I verified that the home_sales temporary table is uncached using PySpark.
