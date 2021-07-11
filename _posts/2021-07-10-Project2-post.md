---
layout: post
Title: Project2-bike.share-prediction
---

This is a group project participated by [John Clements](https://github.com/jkclem) and [Jingjing Li](https://github.com/JingJ-Li), aiming at analyzing and creating predictive models on "Bike Sharing Dataset" at ["UCI Machine Learning Repository"](https://archive.ics.uci.edu/ml/datasets/Bike+Sharing+Dataset#) where core data set is related to two-year log (2011, 2012) from Capital Bikeshare system, Washington D.C. 

The project which is written in Rmarkdown consists of four sections including "introduction", "reading in and subsetting the data", "data exploration" and "modeling". The introduction section highlights the dataset source information, adopted variables,  analysis and modeling as well as required packages. The section of "reading in and subsetting the data" exhibits the codes and process to read in data, converts some numeric variables into factors and splits data into train and test portions. Data exploration section displays a summary table of means and sds of temperature, humidity and windspeed in four seasons,  a contingency table about the weather situation against each season and ten figures reflecting the distribution of bike rentals, temperature, humidity and wind speed at different seasons, bike rentals responding to temperature, humidy, windspeed, season, weather situations and years. Modeling section entails two linear models (multiple linear regression and Poisson regresion) and two ensemble tree models(Random forest and boosted tree) as well as the comparison of these models performance on test data using caret packge which identifies the optimal one.

Several interesting topics are answered as below regarding this project.
* What would I do differently?   
  I probably would not assign full names to the numbers of season, weather situation via codes. Instead, those names may reflect in the introduction. 
  In the plots and tables, temperature, humidity and windspeed may not convert from normalized value to the original value because normalized value can also reflect the effect of variables on response and their interactions. 
   The codes for automatic Rmarkdowns may be different.
   The comparison process of different models may be simplified a little. 
   
* What was the most difficult part for you?  
   It sounds very difficult to choose values of tunning parameter when using train function of caret package for different modeling. 
   In output files by automated Rmarkdown, getting different conclusions per different data is very challenging.
   
* What are yor big take-aways from this project?  
   The major lessons from this project include learn comparing models all based on caret packages, automatic Rmarkdown output of serial data and collaboration with other group members via github.
   
The link to access to the github page created by John Clements, the first group member, is [here](https://jkclem.github.io/bike-share-prediction/). The link of repo site is [here](https://github.com/jkclem/bike-share-prediction).

