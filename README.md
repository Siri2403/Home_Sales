# Home_Sales

## Home Sales Metrics using SparkSQL

This assignment dives in the home sales data and identifies certain key points on metrics like average price for various 
bedrooms and the view rating.

The dataset (home_sales_revised.csv) is processed using SparkSQL, and advanced features like caching and partitioning are
utilized to optimize queries.

## Objectives

1. Analyze home sales data using SparkSQL to answer the following questions:
    Average price of four-bedroom houses sold per year.
    Average price of three-bedroom, three-bathroom homes by year built.
    Average price of three-bedroom, three-bathroom, two-floor homes with ≥ 2,000 sqft by year built.
    Average home price per "view" rating where the price is ≥ $350,000.
2. Optimize queries using caching and partitioning.
3. Compare runtime performance for cached vs. uncached data.
4. Save and query partitioned data stored in Parquet format.
