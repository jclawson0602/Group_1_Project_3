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
- Project_3_Yelp_CSVs Folder: The CSV files of the data gathered from Yelp. Cleaned and structured.
- "project_3_joel_foursquare" Folder:
- "selenas_data_cleaned_mapped" Folder: 

The rest of the files outside of our project folders include our powerpoint presentation, our Entity Relationship Diagram (ERD), and relevant 

Yelp Dataset
--
In this project, the team utilized Yelp’s academic dataset. This dataset was saved in a Tape Archive Format (TAR) which allows multiple JSON datasets to be saved to an uncompressed archive file.  Due to the large size of the dataset file (9 gigabytes) we used a software utility program called 7-ZIP (7-ZIP.org) which was used to access the data. Through the 7-ZIP software program, the JSON data was saved into the following formats: SQL, CSV and Text. 


Data References
--
References for our data include Yelp (https://api.yelp.com/v3), Yelp’s open dataset (www.yelp.com/dataset), and Foursquare (https://api.foursquare.com/v3/places/search). For our API sources, we used Yelp’s fusion API and Foursquare’s Places API.

Leaflet Map
--
Using the Yelp dataset and the Folium library, we were able to create a leaflet map. Folium was used to write the HTML code for our map in a jupyter notebook along with the latitudes and longitudes of locations from restaurants within our Yelp dataset. 
