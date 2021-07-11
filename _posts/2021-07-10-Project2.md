---
layout: post
Title: Project2-bike.share-prediction
---

This is a collaborative project participated by John Clements and Jingjing Li, aiming at analyzing and creating predictive models on "Bike Sharing Dataset" at ["UCI Machine Learning Repository"](https://archive.ics.uci.edu/ml/datasets/Bike+Sharing+Dataset#) where core data set is related to two-year log (2011, 2012) from Capital Bikeshare system, Washington D.C. 

The project which is written in Rmarkdown consists of four sections including "introduction", "reading in and subsetting the data", "data exploration" and "modeling". The introduction section highlighted the dataset source information, adopted variables,  analysis and modelinga as well as required packages. The section of "reading in and subsetting the data" exhibits the codes and process to read in data, convert some  cnumeric variables into factors and split data into train and test portions. Data exploration section display a summary table of means and sds of temperature, humidity and windspeed in four seasons,  a contingency table about the weather situation against each season and ten figures reflecting the distribution of bike rentals, temperature, humidity and wind speed at different seasons, bike rentals responding to temperature, humidy, windspeed, season, weather situations and years. Modeling section entails two linear models (multiple linear regression and Poisson regresion) and two ensemble tree models(Random forest and boosted tree) as well as the comparison of these models performance on test data using caret packge which identifies the optimal one.

The link to access my github pages repo is here. The link to access the rmarkdonw file elaborating the details of the functions,usual repo is here.
