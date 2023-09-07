# Final-Project-Statistical-Modelling-with-Python

## Project/Goals
- Explore the structure and function of API's including Citybikes, Foursquare and Yelp
- Create a dataframe and then a SQLite SQL database from the data extracted from the API's
- Build a regression model and interpret the results of the model

## Process
### I chose Fort Lauderdale, USA as the Citybikes location to download data from
### After getting location details about the 20 citybikes stations, I found Points-Of-Interest within 1000m using the FourSquare and Yelp API's
### I then connected the two dataframes (Foursquare, Yelp) together and performed a visualization using the Station data for my EDA
### Finally, I performed a regression model on a dataset I downloaded from Kaggle and made some conclusions
### Note: I didn't realize that the regression was to be on our FourSquare and Yelp data - the Jupyter sheet simply says "do a regression" so I thought I could choose my own data

## Results
- Two results became apparent:
  1. Broward B-Cycle stations are all located along the beach
  2. For the regression, there is no strong corellation between SAT scores and GPA's

## Challenges 
Figuring out the Citybikes API was very, very difficult because there is almost no documentation supplied

## Future Goals
I would go back and do the regression analysis on proximity of bike stations to Points-Of-Interest
