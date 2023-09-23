# Climate Analysis with SQLAlchemy and Flask

Part 1: Analyze and Explore the Climate Data
Used Python and SQLAlchemy to do a basic climate analysis and data exploration of the climate database. Specifically, used SQLAlchemy ORM queries, Pandas, and Matplotlib.

Used the SQLAlchemy create_engine() function to connect to SQLite database.

Used the SQLAlchemy automap_base() function to reflect tables into classes, and then saved references to the classes named station and measurement.

![image](https://github.com/albertdudek7/Climate_Analysis_with_SQLAlchemy/assets/127783844/afdfc6db-a80d-43a8-a576-14f569182468)


Linked Python to the database by creating a SQLAlchemy session.

Performed a precipitation analysis and then a station analysis.

Precipitation Analysis
Finding the most recent date in the dataset.

Using that date, the previous 12 months of precipitation data were found by querying the previous 12 months of data.

![image](https://github.com/albertdudek7/Climate_Analysis_with_SQLAlchemy/assets/127783844/da5d2701-0dad-475b-aefa-3b37527bfbf7)

Used Pandas to print the summary statistics for the precipitation data.
![image](https://github.com/albertdudek7/Climate_Analysis_with_SQLAlchemy/assets/127783844/1d683a64-1270-41e6-b39c-e49e831fcf67)

Station Analysis
Designed a query to calculate the total number of stations in the dataset.
Designed a query to find the most-active stations.

![image](https://github.com/albertdudek7/Climate_Analysis_with_SQLAlchemy/assets/127783844/4c1da7fd-0cbf-4b92-b1e8-8ef64f1ce867)

Part 2: Design Climate App
Designed a Flask API based on the queries that were developed. 


