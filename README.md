# IPL Predictor using Regression and Classifcation

Welcome to my Data Science Analysis using IPL Data. As I have a passion for Cricket, this sets of analysis will look at how I take a public dataset on Kaggle and attempt to answer some interesting questions.

Background and Introduction

Since its introduction in 2003, T20 has become the star attraction within cricket for its high voltage action and exciting phases of play. As part of its popularity, the IPL (Indian Premier League), formed in 2008, began and kicked off one of the largest annual sports events in the world alongside the Football Premier League and NBA (National Basketball Association) until today. As a result of its increasing demand, teams are spending money towards a variety of avenues to gain a distinct competitive edge. One of these avenues is within data science to analyse player performance and opposition performance. As a result, the analysis of a league like this IPL is of growing importance. 

The data found from Kaggle. It uses two sets of data based from 2008 -2017; match-by-match and ball by ball statistics. The datasets are suitable to extract some key data, provide some statistical descriptive and visualizations and apply some machine learning techniques using Python. In this report, we aim to answer 2 key questions:

What is the best classification algorithm to predict the results of two teams accurately, demonstrating the most important features within it? What is the best regression algorithm to predict a bowler’s runs conceded?

I have taken my code from Kaggle and pushed it onto Github for the remaining future

** This Project was originally completed in 2019**

## Basic Data Analysis

A selection of Data Analysis to have a quick look at the data 

### Top Batsmen and Bowlers in the IPL

![](https://github.com/AadilMalik94/IPL-Predictor-using-Regression-and-Classifcation/blob/main/Images/TopBatsmen.PNG)

![](https://github.com/AadilMalik94/IPL-Predictor-using-Regression-and-Classifcation/blob/main/Images/TopBowlers.PNG)

### BoxPlots of Teams when winning by Runs and Wickets

A boxplot is a standardized way of displaying the distribution of data based on a five number summary (“minimum”, first quartile (Q1), median, third quartile (Q3), and “maximum”). It can tell you about your outliers and what their values are. It can also tell you if your data is symmetrical, how tightly your data is grouped, and if and how your data is skewed.

![](https://github.com/AadilMalik94/IPL-Predictor-using-Regression-and-Classifcation/blob/main/Images/WinningMarginsTeams.PNG)


## Classification

What is the best classification algorithm to predict the results of two teams accurately, demonstrating the most important features within it?
I will be using 4 main methodologies below, with key stats used to demonstrate their accuracy and suitability. 

### K Nearest Neighbours 

![](https://github.com/AadilMalik94/IPL-Predictor-using-Regression-and-Classifcation/blob/main/Images/KNN1.PNG)

![](https://github.com/AadilMalik94/IPL-Predictor-using-Regression-and-Classifcation/blob/main/Images/KNN2.PNG)

![](https://github.com/AadilMalik94/IPL-Predictor-using-Regression-and-Classifcation/blob/main/Images/KNN3.PNG)

### Naive Bayes Classifier 

![](https://github.com/AadilMalik94/IPL-Predictor-using-Regression-and-Classifcation/blob/main/Images/NB1.PNG)

![](https://github.com/AadilMalik94/IPL-Predictor-using-Regression-and-Classifcation/blob/main/Images/NB2.PNG)

![](https://github.com/AadilMalik94/IPL-Predictor-using-Regression-and-Classifcation/blob/main/Images/NB3.PNG)

### Decision Tree

![](https://github.com/AadilMalik94/IPL-Predictor-using-Regression-and-Classifcation/blob/main/Images/DT1.PNG)

![](https://github.com/AadilMalik94/IPL-Predictor-using-Regression-and-Classifcation/blob/main/Images/DT2.PNG)

![](https://github.com/AadilMalik94/IPL-Predictor-using-Regression-and-Classifcation/blob/main/Images/DT3.PNG)

### Logisitc Regression

![](https://github.com/AadilMalik94/IPL-Predictor-using-Regression-and-Classifcation/blob/main/Images/LG1.PNG)

![](https://github.com/AadilMalik94/IPL-Predictor-using-Regression-and-Classifcation/blob/main/Images/LG2.PNG)

#### The Most Important Variables

![](https://github.com/AadilMalik94/IPL-Predictor-using-Regression-and-Classifcation/blob/main/Images/VARIMP.PNG)

### Summary of all the Classifiers

![](https://github.com/AadilMalik94/IPL-Predictor-using-Regression-and-Classifcation/blob/main/Images/SUMMARY1.PNG)

## Regression Analysis 

Now we will be running the bowler's Regression to estimate the total number of runs conceded when they bowl in the IPL

At this point, it is important to remember that we earlier grouped the deliveries data set that is viable for each and every bowler. Having named this as a data strucure, we save this file as a csv and now we call upon it seperately. As with the classification, I have omitted certain columns. You can do so otherwise or keep them at your discretion.

I will be comparing different regression analysis for this section

![](https://github.com/AadilMalik94/IPL-Predictor-using-Regression-and-Classifcation/blob/main/Images/train1.PNG)

![](https://github.com/AadilMalik94/IPL-Predictor-using-Regression-and-Classifcation/blob/main/Images/train2.PNG)

![](https://github.com/AadilMalik94/IPL-Predictor-using-Regression-and-Classifcation/blob/main/Images/train3.PNG)

![](https://github.com/AadilMalik94/IPL-Predictor-using-Regression-and-Classifcation/blob/main/Images/train4.PNG)
