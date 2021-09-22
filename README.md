# World Weather Analysis

## Purpose
Our initial analysis was to reccomend travellers ideal hotels based on one's weather preferences. an API call to OpenWeatherMap was used to collect information on weather conditions around the world, then this information was filtered and displayed to fit customer preferences. In this analysis we want to filter our data to identify nearby hotels. From this dataframe we will choose four cities to create a round trip with. Using the google maps directions api  a travel route between these cities is created along with markers including popup information about each city.

## Breakdown of Analysis
This analysis is completed in three parts. The first part of the analysis is to generate 2,000 random latitude and longitudes. Then an API call is performed with the OpenWeatherMap to retrieve current weather information and add it to a dataframe

[Link to Deliverable 1][https://github.com/c-geisel/World_Weather_Analysis/blob/main/Weather_Database/Weather_Database.ipynb]

The second portion of this analysis is to take in customer input about the preferred weather on their vacation, then use this information to identify possible hotels they can travel to. This information is gathered using a google API and it compiled on an interactive map with markers including information of each destination. 

[Link to Deliverable 2][https://github.com/c-geisel/World_Weather_Analysis/blob/main/Vacation_Search/Vacation_Search.ipynb]

In final part to this analysis, a google API is once again used. Four cities from the earlier dataframe are chosen as a route for one's vacation, a custom layer for the loop of a route to be taken is then shown along with markers including city information for each location. 

[Link to Deliverable 3][https://github.com/c-geisel/World_Weather_Analysis/blob/main/Vacation_Itinerary/Vacation_Itinerary.ipynb]
