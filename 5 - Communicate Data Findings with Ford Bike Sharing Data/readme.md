# Communicate-Data-Finding-Exploration-with-Ford-GoBike-System-Data
## by Gunja Chotai


# Project Table of Contents : 
* Preliminary wrangling
* Structure of dataset
* Univariate Exploration and Analysis
* Bivariate Exploration and Analysis
* Multivariate Exploration and Analysis


# Why this project?
This project is divided into two major parts. In the first part, you will conduct an exploratory data analysis on a dataset Ford GoBike System Data. I will use Python data science and data visualization libraries to explore the dataset’s variables and understand the data’s structure, patterns and relationships. The analysis in this part should be structured, going from simple univariate relationships up through multivariate relationships.

# What will I learn?
After completing this project, I will be able to:

- Supplement statistics with visualizations to build understanding of data.
- Choose appropriate plots, limits, transformations, and aesthetics to explore a dataset, allowing you to understand distributions of variables and relationships between features.
- Create effective visualizations for communicating findings to an audience.


### Data source :
Ford GoBike System Data : https://www.fordgobike.com/system-data
This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area .

### Features :
Trip Duration (seconds) , Start Time and Date , End Time and Date , Start Station ID , Start Station Name , Start Station Latitude , Start Station Longitude ,  End Station ID , End Station Name,  End Station Latitude , End Station Longitude , Bike ID , User Type (Subscriber or Customer – “Subscriber” = Member or “Customer” = Casual) and bike_share_for_all_trip

### Questions to be answered: 
1. What is the distribution of trip duration?
2. Is the trip duration affected by weather( months/seasons)
3. Does the above depend on if a user is a subscriber or customer?


### Summary of findings :
Since the trip duration has a close relationship with bike share company's revenue, I tried to find out what are the key factors affect 
trip duration. It turns out that Weather does not have a big effect on the trip duration but user type does have an impact on trip duration. According the analysis, I found subscribers tend to rend the bikes for longer trips ( generally above 300 minutes ). One possible way to increase revenue is to attract more potential customers and convert more exiting customers to subscribers. 