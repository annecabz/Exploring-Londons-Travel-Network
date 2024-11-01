# Exploring-Londons-Travel-Network

Write three SQL queries to answer the following questions:

What are the most popular transport types, measured by the total number of journeys? The output should contain two columns, 1) journey_type and 2) total_journeys_millions, and be sorted by the second column in descending order. Save the query as most_popular_transport_types.

Which five months and years were the most popular for the Emirates Airline? Return an output containing month, year, and journeys_millions, with the latter rounded to two decimal places and aliased as rounded_journeys_millions. Exclude null values and save the result as emirates_airline_popularity.

Find the five years with the lowest volume of Underground & DLR journeys, saving as least_popular_years_tube. The results should contain the columns year, journey_type, and total_journeys_millions.

Three SQL cells have been created for you in the workbook. To access the AWS Redshift database, you will need to select data using the syntax FROM tfl.journeys.

Note: Please also ensure that you do not change the names of the DataFrames that the three query results will be saved as - creating new cells in the workbook will rename the DataFrame (see image below). Make sure that your final solutions use the names provided: most_popular_transport_types, emirates_airline_popularity, and least_popular_years_tube.