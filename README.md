# Final-Project-Statistical-Modelling-with-Python

## Project/Goals
The goal of this project was to explore the relationship between the availability of free bikes and the characteristics of points of interest (POIs) in Barcelona using data from Foursquare. Specifically, I aimed to build a regression model to predict the number of free bikes available at various locations based on the number and ratings of nearby POIs.

## Process
### Data Collection
I collected data on bike stations and POIs from the Foursquare API. Due to limitations in accessing the Yelp API, my analysis was restricted to Foursquare data alone.
### Data Preparation and Analysis
I prepared the data by aggregating POI characteristics around each bike station and then built an OLS regression model using statsmodels in Python to examine the influence of POI characteristics on the availability of free bikes.
## Results
The comparative quality of API coverage showed that Foursquare provided a sufficient range of POIs for this analysis, despite the inability to incorporate Yelp data for a more comprehensive view. The regression model, however, revealed that neither the number of POIs nor their average ratings significantly predicted the number of free bikes available, as indicated by the model's low adjusted R-squared value and the non-significant p-values of the predictors.

## Challenges 
The main challenges faced during the project included:

- Incomplete data from Foursquare, particularly the lack of ratings for many POIs.
- The small sample size of bike stations, which limited the statistical power of our regression model.
- Inability to access the Yelp API, which restricted our data source to Foursquare alone, potentially limiting the breadth of our analysis.

## Future Goals
With more time, I would:

- Expand the dataset to include more bike stations and possibly wider geographic coverage to improve the model's robustness.
- Attempt to resolve the issue with accessing the Yelp API to enrich our dataset with additional POI data.
- Explore more sophisticated modelling techniques, such as machine learning models, that could potentially capture complex nonlinear relationships and interactions between variables.
