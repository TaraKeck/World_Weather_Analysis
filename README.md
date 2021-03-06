# World_Weather_Analysis

## Overview
The purpose of this analysis was to test the beta site for PlanMyTripp app and adding weather descriptions.  This feature is the perfect add on especially in tourism to give the consumer an opportunity to book travel based on climate and weather conditions.  For the sake of this excercise, I set parameters to the min/max temperature location that I would be most interested in traveling.   Three steps broken down below are:   retrieving weather data, creating a customer travel destination map and creating a travel itinerary map.

## Deliverable 1: Retrieve Weather Data

- Retrieve all of the following information from the API call.
  - Latitude and longitude
  - Maximum temperature
  - Percent humidity
  - Percent cloudiness
  - Wind speed
  - Weather description (for example, clouds, fog, light rain, clear sky)

![image](https://user-images.githubusercontent.com/85530690/126714402-c99af79b-b6fa-4cc6-ae42-7152ecd756a9.png)

- Add the weather data to a new DataFrame 

![image](https://user-images.githubusercontent.com/85530690/126714461-f97249ea-d791-44ae-a338-f5e8fdf10502.png)

- Export the DataFrame as WeatherPy_Database.csv into the Weather_Database folder

- Weather Data Folders Inlcuded:
    - The Weather_Database.ipynb file
    - The WeatherPy_Database.csv file


## Deliverable 2: Create a Customer Travel Destinations Map

- Input statements are written to prompt the customer for their minimum and maximum temperature preferences.

- A new DataFrame is created based on the minimum and maximum temperature, and empty rows are dropped.


- The hotel name is retrieved and added to the DataFrame, and the rows that don’t have a hotel name are dropped.


- The DataFrame is exported as a CSV file into the Vacation_Search folder and is saved as WeatherPy_vacation.csv. 


- A marker layer map with pop-up markers for the cities in the vacation DataFrame is created, and it is uploaded as a PNG. Each marker has the following information:
  - Hotel name
  - City
  - Country
  - Current weather description with the maximum temperature


- The marker layer map is saved and uploaded to the Vacation_Search folder as WeatherPy_vacation_map.png. 

![image](https://user-images.githubusercontent.com/85530690/126715090-d737b1e4-9eb3-478b-a489-96dc488532a9.png)

- Files located in the Vacation_Search folder:
  - The Vacation_Search.ipynb file
  - The WeatherPy_vacation.csv file
  - The WeatherPy_vacation_map.png image



## Deliverable 3: Create a Travel Itinerary Map

- Four DataFrames are created, one for each city on the itinerary. 


- The latitude and longitude pairs for each of the four cities are retrieved. 

- A directions layer map between the cities and the travel map is created and uploaded as WeatherPy_travel_map.png.

![image](https://user-images.githubusercontent.com/85530690/126715714-48da4374-70a8-49f9-a148-6659a5ffa8fb.png)

- A DataFrame that contains the four cities on the itinerary is created. 

- A marker layer map with a pop-up marker for the cities on the itinerary is created, and it is uploaded as WeatherPy_travel_map_markers.png. Each marker has the following information:
  - Hotel name
  - City
  - Country
  - Current weather description with the maximum temperature

![image](https://user-images.githubusercontent.com/85530690/126715608-7ff88515-9596-4496-b878-931cbb64af17.png)


- Files located in the Vacation_Itinerary folder:
  - The Vacation_Itinerary.ipynb file
  - The WeatherPy_travel_map.png image
  - The WeatherPy_travel_map_markers.png image
