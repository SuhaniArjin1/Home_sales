# Home_sales
## Overview
Using my knowledge of SparkSQL I aim to determine key metrics about home sales data. Then I use Spark to create temporary views, partition the data, cache and uncache a temporary table, and verify that the table has been uncached.

## Investigate
1. What is the average price for a four-bedroom house sold for each year?
2. What is the average price of a home for each year it was built that has three bedrooms and three bathrooms?
3. What is the average price of a home for each year that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet?
4. What is the "view" rating for homes costing more than or equal to $350,000? 
5. Analyze the difference in run time using uncached, cached and partitioned data.

## Results
The results are printed as tables in the "Home_Sales.ipynb"
Surprisingly, the query ran with uncached data ran the fastest with a run time of 0.3602 seconds while the query with cached data took the longest with a run time of 0.8371 seconds. It should be noted that this is just one example and may not accuratley represent how caching data affects run time. 

## References 
Data for this dataset was generated by edX Boot Camps LLC, and is intended for educational purposes only.
