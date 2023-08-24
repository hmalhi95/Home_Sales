# Home Sales

Using the Home_Sales_starter_code file provided I used SparkSQL and home sales csv data to find the following metrics:

- The average price for a four-bedroom house sold for each year
- Average price of a home for each year it was built that has three bedrooms and three bathrooms
- Average price of a home for each year that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet
- The "view" rating for homes costing more than or equal to $350,000
  
Next, I used SparkSQL to:
- Create temporary views
- Partitions the data
- Cache and uncache a temporary table, and verifies that the table was cached and uncached

I also compared query time for the "view" rating for homes costing more than or equal to $350,000 query before the table was cached and after it was cached to compare the run time
