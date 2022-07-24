# World_Weather_Analysis
This is the project where we develope and refine a phone application called PlanMyTrip. 

# Overview
The CEO has some reccomendations to imporve the app. In particular, The CEO wants to add the weather description along with the latitude, longitude, city, country, and the Hotel Name for each destination. The tools to conduct the project are Jupyter Notebook and Google Maps. 


# Results
The first step to generate the layer maps is to generate a set of latitudes and longitudes, obtain the nearest city, and generate a API call with the software called OpenWeatherMap.  From here, we have created a DataFrame displaying the city, country, latitude (Lat), longitude (Lng), Maximum Temperature, Humidity, Cloudiness, Wind Speed, and the current weather description. Here is the dataframe shown below, displaying the first 10 rows. 

<img width="883" alt="Screen Shot 2022-07-24 at 11 46 13 AM" src="https://user-images.githubusercontent.com/104328106/180659805-3442143d-ea64-47cf-8142-86bef40e3983.png">

The next step is to retreieve customers preferences to the weather. We then use each customers weather preferences to pinpoint potential travel destinations and nearby hotels. All of the code is presented in a folder called "Vacation_Search". 



# Summary 

