# Big-Data-Analtyics_NYCity-TLC
The New York City Taxi & Limousine Commission (TLC) has provided a dataset of trips made by the taxis in the New York City. The detailed trip-level data is more than just a vast list of taxi pickup and drop off coordinates.  It provides precise location coordinates for where the trip started and ended, timestamps for when the trip started and ended, plus a few other variables including fare amount, payment method, and distance travelled.
The purpose of this dataset is to get a better understanding of the taxi system so that the city of New York can improve the efficiency of in-city commutes.
In this assignment, ONLY the data of yellow taxis for November and December of the year 2017 is considered.

Data can be downloaded from:
https://www1.nyc.gov/site/tlc/about/tlc-trip-record-data.page

# IMPORTANT: Before partitioning any table, make sure you run the below commands.

SET hive.exec.max.dynamic.partitions=100000;
SET hive.exec.max.dynamic.partitions.pernode=100000;
