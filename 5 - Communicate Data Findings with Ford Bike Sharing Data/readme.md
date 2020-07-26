# Communicate Data Finding Exploration For ` Ford-GoBike-System-Data`
## by Gunja Chotai

# Overview
> Here I selected Ford GoBike System Data: https://www.fordgobike.com/system-data as data source for exploration data.Data source includes information about a bike-sharing system which is provided in the San Francisco Bay area.
Collect all given .csv files for year 2018 and combine all data together as one dataset for analysis purpose. 

> This project has main two parts. 
> - In the first section, I am preparing an exploratory data analysis on selected dataset. In this I will use Python's numpy, pandas, matplotlib and seaborn library for data visualization and explore the dataset relationships. In the analysis part we should do univariate, bivariate and multivariate relationships exploration.
> - In the second part, I am preparing my findings from relationship exploration and try to convey them to others through an explanatory analysis. 
For this, I will prepare a slide deck that will help me to create proper convenable visualizations to others.

# Dataset
>In this document dataset contains ford go bike sharing trip data. There is approximately 18,63,721  with 14 features like as duration_sec, start_time, end_time, start_station_id, start_station_name, start_station_latitude, start_station_longitude, end_station_id, end_station_name, end_station_latitude ,end_station_longitude, bike_id, user_type and bike_share_for_all_trip. 
Most variables are 6 numerical, and others are 2 datetime, 6 object type. For clean dataset convert the data type for start and end time to be datetime64.

# Summary of Findings
> From Exploration distribution of the trip duration is that most of the trip is on an average about 10 mins. 
And From June to Auguts in 2018 has the most trip held for longest duration. Other month have not significant difference.
Most of the longest trip held in summer, for almost average 15 mins. But we can't find more significant difference of trip duration all four seasons. 
Mostly subscribers take bike on rent for long trip like more than 300 minutes. And normal user can take bike rent for an average 100 minute.

# Key Insights for Presentation
> season can't affect to bike rent system because san francisco bay area has almost same wheather throughout the years.
And User type didn't make any diffrence for trip duration.
