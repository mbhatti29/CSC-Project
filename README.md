# CSC 599.70 Introduction To Data Science - Final Project

## Overview

Climate change has certainly become one of humanity's greatest threats.  It is defined as the change in global or regional patterns in climate.  Advancements in technology have allowed scientists to collect various types of data regarding our changing planet, which has led to many significant discoveries.

The primary theories we looked into and the objectives we aimed to achieve by analyzing a few selected datasets relate to the effects of global and regional increases in temperature, and its progression due to greenhouse gas emissions.  More specifically:
* Linear and non-linear regressional analysis on average global and regional temperatures
* Geographical correlation to increasing temperatures
* Prediction of carbon dioxide atmospheric concentration
* Impact of fossil fuel combustion, carbon dioxide, and other greenhouse gases

## Pre-processing and Data Exploration

We used the open source libraries [Pandas](http://pandas.pydata.org) and [Matplotlib](http://matplotlib.org) in order to clean and visualize our data. 

![alt text](https://github.com/brandonmchin/Intro-Data-Science/blob/master/Final-Project-Climate-Change/Images/avg_global.png "Average Global Temperatures")

In particular, our datasets were **Time Series**, which are considered data points collected in constant time intervals.  Time series are typically used to observe long-term trends in order to forecast predictions.  However, time series are relatively difficult to work with because:
> 1. they are time dependent, meaning each observation is not independent
> 2. they consist of seasonal trends; in our case, temperatures fluctuate between seasons and are not necessarily relevant to long-term climate changes

In addition to our iPython notebooks, there is a python script in which we handle much of the processing, such as extrapolating features, handling missing data, identifying outliers, and plotting.

## Model Fitting and Metrics
