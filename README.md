# World-Weather-Analysis
Plan my trip is a top travel technology company that specializes in internet related services in the hotel and lodging industry. Jack is the head of analysis for the user interface team.
We are tasked to export the data, clean it and use the weather data to choose the best cities for a vacation based on certain weather criteria. And then map these cities using jupiter G maps and google places API
At the most fundamental level, Jack needs help answering a question: How might we provide real-time suggestions for our client's ideal hotels? Your first task was to define what you meant by "ideal." So, over the course of the conversation, you narrowed that to hotels that were 
1. within a given range of latitude and longitude and that 
2. provided the right kind of weather for the client.

# Basic Project Plan
Here's an outline of the project plan:

- Task: Collect and analyze weather data across cities worldwide.
- Purpose: PlanMyTrip will use the data to recommend ideal hotels based on clients' weather preferences.
- Method: Create a Pandas DataFrame with 500 or more of the world's unique cities and their weather data in real time. This process will entail collecting, analyzing, and visualizing the data.

The analysis of the data will be split into three main parts, or stages.

### Collect the Data

- Use the NumPy module to generate more than 1,500 random latitudes and longitudes.
- Use the citipy module to list the nearest city to the latitudes and longitudes.
- Use the OpenWeatherMap API to request the current weather data from each unique city in your list.
- Parse the JSON data from the API request.
- Collect the following data from the JSON file and add it to a DataFrame:
1. City, country, and date
2. Latitude and longitude
3. Maximum temperature
4. Humidity
5. Cloudiness
6. Wind speed

### Exploratory Analysis with Visualization

- Create scatter plots of the weather data for the following comparisons:
1. Latitude versus temperature
2. Latitude versus humidity
3. Latitude versus cloudiness
4. Latitude versus wind speed

- Determine the correlations for the following weather data:
1. Latitude and temperature
2. Latitude and humidity
3. Latitude and cloudiness
4. Latitude and wind speed

- Create a series of heatmaps using the Google Maps and Places API that showcases the following:
1. Latitude and temperature
2. Latitude and humidity
3. Latitude and cloudiness
* Latitude and wind speed

### Visualize Travel Data

Create a heatmap with pop-up markers that can display information on specific cities based on a customer's travel preferences. Complete these steps:

- Filter the Pandas DataFrame based on user inputs for a minimum and maximum temperature.
- Create a heatmap for the new DataFrame.
- Find a hotel from the cities' coordinates using Google's Maps and Places API, and Search Nearby feature.
- Store the name of the first hotel in the DataFrame.
- Add pop-up markers to the heatmap that display information about the city, current maximum temperature, and a hotel in the city.

## Results

![Fig10](https://user-images.githubusercontent.com/89896665/216824262-fca96a56-225e-4758-a972-00ec813d565a.png)

![Fig11](https://user-images.githubusercontent.com/89896665/216824275-f14cedc0-521a-4cfa-898f-2f5a51c3774f.png)

![Fig12](https://user-images.githubusercontent.com/89896665/216824290-70403871-2d63-4aea-96f1-2e5a887682c3.png)

![Fig13](https://user-images.githubusercontent.com/89896665/216824314-499e2ede-a80f-4495-a41c-006a64cb3ebd.png)


