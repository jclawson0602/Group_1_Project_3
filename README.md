# Group_1_Project_3
Group Members
--
--Zac Williams
--Joel
--Cole
--Justin
--Selena

Project Overview and Purpose
--
For our project, we focused on following the data engineering process to extract, transform, and load restaurant data. Firstly, we extracted data from websites including Yelp and Foursquare using API connections as well as sourced data from a large dataset provided by Yelp. Secondly, we transformed the data we collected by dropping null values, changed the data types of several columns and selected specific attributes to insert data into DataFrames. Third, we created an Entity Relationship Diagram with the schema from our DataFrames and used them to load the data tables into a PostgreSQL database. Lastly, we used our DataFrames to create Leaflet map and used SQLAlchemy to pull our database data into Jupyter Notebook to store it for future use.  

By utilizing APIs, Python libraries, html and a PostgreSQL database, the purpose of our project was to create a map using restaurant data along with storing said data for future use through SQLAlchemy and to display our skills in creating an ETL pipeline. Originally, our goal was to get data from 5 or more sources and compare their records; however, complications with setting up APIs had redirected our goal to its current state. 

File Organization in our GitHub Repository
--
- Project_3_Yelp_CSVs Folder: The CSV files of the data gathered from Yelp including DataFrames from Chicago, Los Angeles 
