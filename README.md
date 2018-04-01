# Ames-Housing-Data

## Domain
This dataset describes hosuing value in Ames, Iowa from 2006-2010.

Past usage of the dataset incclude regression diagnostis by Dean De Cook at Truman State University in 2011 where he discusses his previous use of the Boston Housing Data Set and suggests methods for incorporating this new data set as a final project in an undergraduate regression course.
https://ww2.amstat.org/publications/jse/v19n3/decock.pdf

## Problem Statement
For a house with a given set of features we will use a regression model to predict the median value of the home.

In other words is it possible to predict the median value of a home in Ames, Iowa n by its descriptive features with more certainty than using the mean or most common class.

## Dataset and Inputs
The data set contains 1460 observations and 79 explanatory variables (56 categorical, 23 numeric) that are involved in assessing home values.

The dataset has 1460 rows and 80 columns and uses up 608K GB in memory.

## Solution Statement
A solution to this problem will be a regression model such as a linear regression, Lasso, Ridge, or a SVR.

## Benchmark Model
Given that we seek a regression model a good naive benchmark would be to guess the mean value.

## Evaluation Metrics
The dataset is not evenly distributed as most median values of the home are between 100k-200k. We can use the success of the model measuring against the MSE and determine if our model predicts the correct median value of the home more reliably than the MSE or R^2.