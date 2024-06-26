# Decoding Crime in New York City 

## Group Name: SafeCity

### Team Members 

### Pranav Menon
- Major: Data Science 
- Currently working in a IoT based firm as a Senior Engineer
- Skills: Data Acquistion, Data Cleaning, Visualizations 

### Min Sung Kim
- Major: Data Science
- Currently a student
- SKills: Data Analysis, Data Acquisition, Data Cleaning

### Brian Kong 
- Major: Data Science 
- Currently working as a Business Intelligence Engineer as part of a Data Warehousing team
- Skills: Documentation, Data Acquisition, Cleaning, and Visualizations

### Josh Lister
- Major: Data Science
- currently a Technical Project Manager at software company that designs clinical trial systems
- Skills: Data Acquistion, Visualizations, Data Analysis 


## Project Description 

Crime is a severe issue that affects society negatively in many ways. In the United States, there are thousands of crimes that are occur in every city. This can cause financial and psychological stress when dealing with aftermaths of crimes such as medical treatments of victims, replacement of damaged properties, etc. As crime rates are increasing day by day, it deteriorates safety for citizens which can cause discomfort and anxiety for the throughout the affected areas. New York City is a popular destination for travelers due to tourism and business travel. Mapping out crime hotspots would be extremely beneficial for people who are unfamiliar with the city. For example, if certain areas of the city are prone to carjacking then it might make sense to pay for parking space in a garage to reduce risk. On the contrary, it would make sense for tourists to spend time in areas less prone to crime. The information that can be gathered from this project will be useful for both residents and visitors.

The objective of this project is to do an analysis on crimes in New York city to allow police, citizens,and tourists to better maneuver around the city. By understanding the various relations to crimes and by understanding the locations of these crimes, a better and efficient system could be created to track crime and keep people and their property safe. The analysis can then be further applied to any city around the world.

We will be investigating New York City by examining data from each of the five boroughs; the Bronx, Brooklyn, Manhattan, Queens, and Staten Island. The locations of each crime within the crime data provided by the City of New York are based in latitude and longitude. In order to get a better understanding of the exact location, we will convert this location to a street address using reverse geocoding. Additionally, we are also conducting analysis on what types of crimes are common and dangerous in each section in order to find specific solutions to those crimes by producing an analysis report with graphs, charts, and explanation.

## Dataset Description 

### NYPD Data

NYC crime data, which is published by the police department (NYPD) dates from 2006 to 2020. (The dataset contains reported crimes including felonies, misdemeanors, and violations. The data is available at https://data.cityofnewyork.us/Public-Safety/NYPD-Complaint-Data-Historic/qgea-i56i. The main reason for choosing this dataset is that it is directly obtained from NYPD and has a substantial amount of data to conduct EDA. The dataset contains 35 columns and has around 0.5 million rows for each year. It is a mixture of integer, object, and float type data. There are a total of 7,375,993 complaints spanning across 14 years. This dataset was last updated on July 7, 2021 and is owned by NYC OpenData.

### Reverse Geocoding

Geocode Earth development server was used to obtain information on the street address where the crime took place based on the latitude and longitude. This dataset is used to complement the main NYC crime dataset by providing street addresses based on the coordinates of each incident. Geocode Earth provides a framework for both Forward Geocoding and Reverse Geocoding. For this project, the team utilized the Reverse Geocoding API to integrate our dataset with the street addresses.


## Files in Github

### NY_crime_data_acqusition_Final.ipynb

This file contains the python code for getting crime data for 5 years (2016 - 2020). 

### api_call.py

This file contains the code to get API request for the reverse geocoding. 

Note: The URL has been redacted from this file as it is the private Dev server of Geocode Earth. Please retrieve your own API URL from Geocode Earth,or contact the team with questions

### NY_crime_data_pre-processing_Final.ipynb

This file contains the python code for the data pre-processing that involves data cleaning and data imputation of the datasets. 

### DSCI591 EDA.ipynb

This file contains python codes for EDAs for New York Crime analysis. 

Note: This python code requires the csv file called ny_fin.csv. 

### Tableau Workbook Link

This file contains the tableau link that shows EDAs for New York Crime analysis.

Note: Due to tableau files not being able to upload into github, we provided a tableau link that shows the EDAs for New York Crime analysis. 

