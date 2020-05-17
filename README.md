# A Comprehensive Big Data Analysis Using Spark

Link of the Jupyter Notebook: [Link](https://github.com/Kooroshoo/Big-data-project/blob/master/pyspark_code.ipynb)

The NY taxi commission has provided the data of their taxi for free in order to understand better how their service
works. [Link](https://www1.nyc.gov/site/tlc/about/tlc-trip-record-data.page)
They contain trips that were done by different kinds of taxi companies in the last few years.
From where they went, to where, and how much they paid, when, etc.

Our goal is to understand the different kinds of traffic that exist between the different zones.

We would like to create a graph
• Create a Spark program that reads the data, identifies categories of the trips (hint: Clustering?) and creates a
profile (meaning a set of characteristics) for each category (hint: statistics). Then create a graph in which every
node represents an area and an edge between two nodes means a set of trips that have been done between
them. The edges will be of different type, one type for every category (hint: a solution can be use a graph db,
but can be done even with Spark and DataFrames)
• Identify the top-5 drivers, i.e., drivers that have done the most trips, the longest distance, have made the most
money, etc.
• Identify the best locations, i.e., the locations with the most pickups, the most drop-offs,
• Quantify the total pick-up and drop-off by time of the day (per hour) and per location, as well as overall.
• Illustrate how the fare changes over time (overall fares collected throughout the day, per hour, location, and
also overall).
• Extra: Any other kind of analysis you can think about is welcome to be added in the project.
Analyze the results, meaning comment on the observations that you see.
