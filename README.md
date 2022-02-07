# World Weather Analysis
The purpose of this project is to create an app that will help the user search for vacation destinations, based on weather preferences, with the initial criteria being an input temperature from the user.

The list of cities was created using numpy to generate random coordinates, and then pairing those coordinates to the nearest city with the aid of citypy.

After the cities were obtained, a data frame was created with the cities weather characteristics with the use of the Open Weather Map API.

After the weather data was obtained, then a list of hotels from each city was obtained with the use of google cloud API, and extracting the hotel name and current weather description, and mapping it into a google maps figure, with a marker layer.

Then four cities were selected and using the directions layer, a map with the starting and ending points and three waypoints with driving directions between the four was obtained and mapped.

Finally a marker layer was added between those four cities, with the relevant information for each one, such as the city, country, hotel  name and current weather.
