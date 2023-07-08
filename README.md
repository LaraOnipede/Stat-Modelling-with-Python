# Final-Project-Statistical-Modelling-with-Python

## Project/Goals
Source and access data using APIs
Clean and transform raw data using python
Load data into database using python
performing EDA on data usinf statistics and visualization
Demonstrates a relationship between the number of bikes in a particular location and the characteristics of the POIs in that location.


## Process
Accessed the citybike API for bike stations in Austin Texas
Accessed the foursquare and yelp APIs for point of interests and data for Austin Bike stations
Cleaning and manipulating returned JSON from APIs to extract the attirbutes of interest
Joining the datas colleceted from the citybikes, foursquare and yelp APIs
Explorative analysis of data using visualization
Linear regression model showing how dependent Number of bikes is on distance


## Results
(fill in what you found about the comparative quality of API coverage in your chosen area and the results of your model.)
Yelp API has a more robust attributes of the POIs. It contains review_count and rating which are highly relevant
Apart from the review_count and ratings, I also found out that the number of POI(restaurants) returned by the  yelp API is higher than that of foursquare
I must say that foursquare API contains category id which is not present in the yelp API, but which could be a useful primary key
There is no significant correlation between the Number of bikes and distance


## Challenges 
API limits
Disparity between data extracted from the APis
Time constraint
Lack of sufficient statistical data for building model

## Future Goals
(what would you do if you had more time?)
Explore data from APIs for more statistically relevant data
Build a more significant model for predicting the number of bikes in a bikes station based on the attributes of the POIs around the station.
