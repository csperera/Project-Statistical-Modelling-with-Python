# Final-Project-Statistical-Modelling-with-Python

## Project/Goals
- Explore the structure and function of API's including Citybikes, Foursquare and Yelp
- Create a dataframe and then a SQLite SQL database from the data extracted from the API's
- Build a regression model and interpret the results of the model

## Process
I chose Fort Lauderdale, USA as the Citybikes location to utilize for this project. After getting location details about the 20 citybikes stations, 
I found Points-Of-Interest within 1000m using the FourSquare and Yelp API's.  For both the Foursquare and Yelp API's I extracted the distance
in metres away from the bike station as the primary datapoint. I then connected the two dataframes (Foursquare, Yelp) together and performed visualizations
including boxplots and scatter plots in order to explore the dataset.  Finally, I performed a regression model on a the combined dataset.  

## Results
- Two results became apparent:
  1. Broward B-Cycle stations are all located along the beach
  2. The proximity of bike stations to points-of-interest are not statistically significant
  Ultimately one should note that it is the proximity to the beach, not points-of-interest that seem to be the major factor

## Challenges 
Figuring out the Citybikes API was very, very difficult because there is almost no documentation supplied

## Future Goals
I think it would be interesting to go back and measure bike stations distance from the beach in linear metres versus usage, and see
if there was a relationship
