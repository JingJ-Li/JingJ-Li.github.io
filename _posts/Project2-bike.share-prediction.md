---
type: post
Title: Project2-bike.share-prediction
---

This is a collaborative project participated by John Clements and Jingjing Li, aiming at analyzing and creating predictive models on "Bike Sharing Dataset" at ["UCI Machine Learning Repository"](https://archive.ics.uci.edu/ml/datasets/Bike+Sharing+Dataset#) where core data set is related to two-year log (2011, 2012) from Capital Bikeshare system, Washington D.C. 

The project consists of four sections including introduction, reading in and subsetting the data, data exploration and modeling. 
The data set mainly contains information about the weather on a given day, when the day was (date, season, month, and year), and whether the day was a holiday or working day as well as bike rental counts including casual, registered riders and total number of bike rentals (`cnt`).

In our study the total number of rentals on a given weekday (here `r params$dayName`) will act as the response,  which makes more sense for bike rental business compared to only the casual or the registered . Explanatory variables comprise the weather variables, the season, and the year. The weather related variables are `temp` (normalized temperature), `hum` (normalized humidity), `windspeed` (normalized wind speed), and `weathersit`. The variable `weathersit` is a factor going from 1 to 4, with 1 being nice weather and progressing to 4, which covers severe weather conditions. The `season` variable is a factor for the four seasons, and `yr` is the year.

We analyze the data using plots and tables to see the distribution of bike rentals, the weather situation of different seasons and construct different models (two linear and two tree models) to predict bike rental numbers affected by `season`, `yr` and weather situations represented by `temp`,`hum` and`windspeed`, compare those models and identify the best one.

The link to access my github pages repo is here. The link to access the rmarkdonw file elaborating the details of the functions,usual repo is here.
