# Coursera_Capstone

## Business Problem
In this project, we will try to find an optimal location for opening a new GYM. The problem is targeted at stakeholders who want to start a gym in toronto,canada. We will try to detect locations that are not already crowded with gyms. We would also prefer locations as close to the city center as possible. We are interested to identify ideal locations in toronto for opening a gym as increasing number of people are becoming health consious and hence want to go to a gym which is not far from their houses. 

## Data Description
The data that will be used in the project.

Data Source 1 – Neighborhood Data
The  dataset about neighborhoods of toronto will be extracted from a pre-prepared JSON file from the IBM cloud server and simply run a wget command to access the data.
Features such as borough, neighbourhood, postal code will be extracted.

Data Source 2 – Geographical Coordinates
Geographical coordinates for each neighborhood will be obtained with the aid of GEOPY Library such as latitude and logitude.

Data Source 3 – Venue categories
I will use the Foursquare API to retrieve venues, using the coordinates obtained in Data Source 2 above.
