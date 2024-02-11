Initiated the pyspark in the colad and loaded the  data in the CSV file into the dataframe.
Created a temporary view of the DataFrame.
Answered the below questions with the sql query
What is the average price for a four bedroom house sold in each year rounded to two decimal places?
 What is the average price of a home for each year the home was built that have 3 bedrooms and 3 bathrooms rounded to two decimal places?
 What is the average price of a home for each year built that have 3 bedrooms, 3 bathrooms, with two floors,
 and are greater than or equal to 2,000 square feet rounded to two decimal places?
 What is the "view" rating for the average price of a home, rounded to two decimal places, where the homes are greater than
or equal to $350,000? Although this is a small dataset, determine the run time for this query?
Cache the the temporary table home_sales
Check if the table is cached
Using the cached data, run the query that filters out the view ratings with average price
 greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.
 Partition the home sales dataset by date_built field
 Read the parquet formatted data.
 Create a temporary table for the parquet data.
  Run the query that filters out the view ratings with average price of greater than or equal to $350,000
 with the parquet DataFrame. Round your average to two decimal places.
 Determine the runtime and compare it to the cached version.
 Uncache the home_sales temporary table
 Check if the home_sales is no longer cached
 Dowloaded the file to the local and uploaded in the Git Repository.