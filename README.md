# Maverik-Sales-Analysis
This contains the R-Files for the analysis of Sales Prediction for Maverik

## Overview

This repository contains the code and resources for the Maverik Sales Prediction Project. The project aims to develope a predictive model for Maverik to get an idea of sales for the new stores they want to open based on historical data. They need correct predictions for a new store's sales in its first year for the company’s financial planning and return on investment (ROI) calculations. 

## Table of Contents

- [Introduction](#introduction)
- [Business_Problem](#business_problem)
- [Team_Contribution](#team_contribution)
- [Individual_Contribution](#individual_contribution)
- [Solution](#solution)
- [Recommendation](#recommendation)
- [Difficulties](#difficulties)
- [Learnings](#learnings)

## Introduction

With the recent acquisition of 'Kum & Go', Maverik, a quickly growing retail convenience store network, doubled its number of stores and now operates over 400 sites throughout the western United States. Maverik plans to build about 30 new stores a year as part of its aggressive growth strategy, thus these openings are an important component of their business planning. The difficulty they confront is forecasting sales for these new stores with enough accuracy for their first year of business, which is essential for careful financial planning and the preparation of first-rate return on investment documentation. Maverik is working to create a highly efficient data-driven solution that can offer accurate and trustworthy sales projections for these new store openings in order to overcome this difficulty. 

## Business_Problem

Maverik aims to improve the accuracy of financial planning and ROI documentation for newly opened convenience stores. The project uses qualitative data and quantitative data to increase the accuracy of predictions. To generate daily, seasonally sensitive sales projections for important product categories, an ensemble of forecasting and regression models in R are being developed. As a result, Maverik will be better equipped to allocate resources efficiently, pinpoint lucrative locations, and make overall financial decisions. 

## Team_Contribution

Our efforts as a cohesive team in solving Maverik's business issue are critical to the project's accomplishment. We worked together to conduct in-depth exploratory data analysis, utilising our varied expertise to analyse and comprehend the qualitative data and store-level time series. Together, our knowledge of supervised regression and statistical modelling allows us to create a strong ensemble of R forecasting models.
We came to a conclusion of one person taking one type of model foward and then comparing the results by the same metric. Together, we made sure the model works properly to produce daily sales projections for important product categories that are subject to seasonal fluctuations. We were dedicated to fulfilling project milestones and producing final materials that greatly improve the accuracy of financial plans and ROI documents before the deadline by actively engaging in both the modelling and exploratory data analysis phases. 

## Individual_Contribution

After completing the EDA on the datasets provided, we moved forward to data cleaning and then to model creation. 
We tried various models that gave us varied results. I helped construct a collection of forecasting models in R by utilising my knowledge of supervised regression and statistical modelling. I started out with a prophet model which is supposed to give efficient results for a time-series analysis. But here we had 4 target variables which made it difficult for the model to be made with the expected results. 

Adding different regressors for one target variable was another option I tried to explore but I did not get the results as expected. 

## Solution

We ended up with a model which was an ensemble of ARIMA and ETS Models since we had 4 target variables to predict and no single model that addressed the multi-targeted variables and gave eficient results worked. 

## Recommendation

Our Final Model was ARIMA/ETS which outperformed the benchmarks that were provided by Maverik. 
The final recommendations would include:
1. Adopt the ARIMA/ETS Ensemble Model for daily sales forecasts.
2. Have a coninuous model evaluation and improvement with more data over time.
3. Put a little more investment in data collection for the data quality and quantity.

## Difficulties

The major issues we faced while doing analysis was the time-series analysis. It is such a broader umbrella term which has so much in it and to learn all of that in so little time and implement that on our datasets was a bigger task. 

## Learnings

My particular learnings from this project is both technical and interpersonal. 
For technical, I worked on R and learnt there are so many inbuilt libraries that can be used for data analysis directly. 
Then the importance of your data and cleaning it so that you can use it to it's full extent. 
For interpersonal skills I learnt how to work in a team and how to manage time according to everyone and to put in your best work. 
