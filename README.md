# Insurance-Agency-Performance-Analysis & Agency segmentation

## A Rutgers 2019 Data Science & Visualization Program

### Amit Kumar Raut, Brown Varghese, Krunal Panchal, Luis Davalos, Radha Mahalingam

## Quick Summary

This project implements Machine Learning algorithms using Supervised ML techniques like Regression and classification techniques. We have taken up a practical industry example to implement these techniques.  We intend to implement a full pipeline beginning with data cleaning, data transformation, implementing ML algorithms and finally linking to the data visualization.  

We are using Insurance industry (Property / Casulty as well as Life Insurance ) dataset, which has their policy, premium and claim / loss information for the period between 2005 to 2015.  We are also taking the US Census data for the same period, which has the total insurable population for each US state, area of the state in sq. miles.  We would like to train the ML algorithm with this data, so that given the dependent variables like insurance product, insurable age and state, the model could predict the agency performance which will aid in agency segmentation.

The following is the details of the dataset, which we were able to obtain from Kaggle.

https://www.kaggle.com/moneystore/agencyperformance/version/1


An insurance group consists of 10 property and casualty insurance, life insurance and insurance brokerage companies. The property and casualty companies in the group operate in a 17-state region. The group is a major regional property and casualty insurer, represented by more than 4,000 independent agents who live and work in local communities through a six-state region. Define the metrics to analyse agent performance based on several attributes like demography, products sold, new business, etc. The goal is to improve their existing knowledge used for agent segmentation in a supervised predictive framework.

## Inspiration

a. Summary stats by agency
b. Product line: Commercial Line/Personal Line wise analysis
c. Agency wise - state wise - distribution of Retention ratio (Top 10)
d. Quote system wise hit ratio distribution (also by PL/CL)
e. Add few more based on your understanding of the data
•	Growth rates from 2006 to 2013 have to be computed and converted to independent attributes and include in the data for modeling.
•	Compute Hit ratio based on bounds and quotes for each Quotes system
•	Compute required aggregations at Agency id and state and year
•	Decide if binning the data works for this situation

## We intend to explore the following approaches:

a. Model Building - Either Regression or classification
b. Pattern extraction - Classification Model
c. Patterns from the data using Decision Trees

## Project Plan

![](/images/Project_plan.png)