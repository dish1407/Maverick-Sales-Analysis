# Maverik-Sales-Analysis
This contains the R-Files for the analysis of Sales Prediction for Maverik

## Overview

This repository contains the code and resources for the Maverik Sales Prediction Project. The project aims to develope a predictive model for Maverik to get an idea of sales for the new stores they want to open based on historical data. They need correct predictions for a new store's sales in its first year for the company’s financial planning and return on investment (ROI) calculations. 

## Table of Contents

- [Introduction](#introduction)
- [Business Problem](#businessproblem)
- [Team Contribution](#teamcontribution)
- [Contributing](#contributing)
- [Solution](#solution)
- [Recommendation](#recommendation)
- [Difficulties](#difficulties)
- [Learnings](#learnings)

## Introduction
With the recent acquisition of 'Kum & Go', Maverik, a quickly growing retail convenience store network, doubled its number of stores and now operates over 400 sites throughout the western United States. Maverik plans to build about 30 new stores a year as part of its aggressive growth strategy, thus these openings are an important component of their business planning. The difficulty they confront is forecasting sales for these new stores with enough accuracy for their first year of business, which is essential for careful financial planning and the preparation of first-rate return on investment documentation. Maverik is working to create a highly efficient data-driven solution that can offer accurate and trustworthy sales projections for these new store openings in order to overcome this difficulty. 

## Business Problem

To run this project we would require any platform that supports a .ipynb notebook i.e. Python Programming. 
The libraries that are used in this include pandas, numpy, matplotlib, matplotlib.pyplot, sklearn.metrics, seaborn, os, prettytable, warnings, sklearn, xgboost, lightgbm. 

## Team Contribution
The above-mentioned libraries can be installed using 'pip install library_name'. 

## Contributing

After completing the EDA on the datasets provided, we moved forward to data cleaning and then to model creation. 
We tried various models that gave us varied results. I started out with a random tree forest model taking the historical data which had information including the demographics of the borrower. The few things that the Random Forest Model did was accuracy and robustness. 
After that, we moved on to other types of models including the Logistic Regression Model, LGBM Classifier Model, and XGB Classifier Model. 
Among all those models the model that gave the most promising results for the data that we used was the XG Boost Classifies Model. It gave us a high degree of accuracy and was a model that is faster to train as well. The borrower's income, work situation, and debt-to-income ratio were among the variables the model was able to pinpoint as being the most reliable indicators of default. 
The top predcitors for the XGB Model are:
1. External Source
2. Age
3. Loan Terms
4. Loan Purpose
5. Employement

My particular contribution to the project included exploratory data analysis followed by data cleaning. Then I developed a Random Forest Model which gave us an idea to move forward and try other models to get better results. I also collated different notebooks into one single one and wrote the content to explain what we have been doing so far. Error resolution or removal of inconsistencies was also one of the key contributions I made as a team member. 

## Solution

The XGB Model can clearly help Home Credit to reduce its default rates by a significant percentage.  This is due to the model's ability to pinpoint the elements most closely associated with default, including the income, employment, and debt-to-income ratio of the borrower. 
This model gives a better assessment of a borrower to Home Credit so that they can identify whether taking this risk is worth it or not. The default or no default information can be used in making better decisions in the future which makes their profit rates go higher. 
This also means that the customer is getting a premium experience by getting to know all the factors and information involved in taking a loan. they can make better decisions about their financial situations if they know their standing in the credit assessment. 

## Recommendation

Our recommendation for Home Credit is to implement this XGB Model which will give them the results that they need to increase their profitability as well as their market reach. 
Some points that Home Credit can take into account is making sure that the data they use for their model prediction is accurate and complete because having too many error or too many missing values can skew the final results. 
Another point that should be considered is to monitor the model on a regular basis. As long as the model is giving us desired results or may be results better than that, the company is good to go. But if the results start to decline, they need to take a look at the model and investigate further. 

## Difficulties

The major issues we faced while doing analysis was the size of the data set, it had millions of rows where half of the columns had missing values. Which led to another problem of finding out the KPIs, which metric to use or which to leave out. 

## Learnings

My particular learnings from this project is both technical and interpersonal. 
For technical, I worked on Python and learnt there are so many inbuilt libraries that can be used for data analysis directly. 
Then the importance of your data and cleaning it so that you can use it to it's full extent. 
For interpersonal skills I learnt how to work in a team and how to manage time according to everyone and to put in your best work. 
