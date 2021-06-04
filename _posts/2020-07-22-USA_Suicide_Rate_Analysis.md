---
title: "USA Suicide Rate Analysis"
layout: post
tag: 
- Data Analysis 
- python
- Data Preperation
- EDA

headerImage: true
projects: true
hidden: true # don't count this post in blog pagination
description: " "
category: projects
author: Bhushan Suryawanshi 
externalLink: false
---

<p align="center">
  <img width="460" height="300" src="/assets/images/suicide.png">
</p>

## USA Suicide Rate Analysis
<p align="justify">

#### Introduction – 
We are facing pandemic and whole world is working from home. I am also practicing work from home and I can see that 
being at home 24hrs and not able to go out does build frustration. Same might be case with others (kids, teenagers, singles etc). 
They locked themselves home and that’s why we have seen protests emerging around the world to open the work places. 
If we keep this restricted work for longer it will definitely build depression and can  cause “Suicide”. 
My organization is continuously conducting virtual sessions with psychologists and motivational speakers to ease these type of tensions. 
This led me to check what is historical data is saying about Suicides. If we know the suicide rate and able to predict 
which age group is more affected, we can enhance response to depressed individuals. 

#### Research questions -
1. Is the suicide only be seen in low income house hold because they don’t have income to pay their debt as well as regular day to day expenses? 
2. What is the rate in each country? 
3. Is Suicide rate affected recently (decreasing/increasing)?
4. Does age affect suicide rate?
 
####Approach – 

Plotting data using different visualization methods will provide details on the data. Find relationship between different variables. 
Create correlation martrix. Identify dependent and independent variables in the dataset.  Apply appropriate model as per the EDA. 
Test the model and predict results using confusion matrix.

***How your approach addresses (fully or partially) the problem?***

The approach mentioned above will give insights on the data. It will help to identify the data types and relations in 
the variables. The exploratory analysis of the data will help in identifying which data set suits the problem statement. 
It will address if there is any cleaning process required? Also getting more appropriate model will give us higher 
accuracy on prediction of suicide rate.
 
</p>

#### DataSets:

***Dataset-1***: has 12 columns and 27000 rows. This compiled dataset pulled from four other datasets linked by time and place, 
and was built to find signals correlated to increased suicide rates among different cohorts globally, across the socio-economic spectrum.
[Here](https://www.kaggle.com/russellyates88/suicide-rates-overview-1985-to-2016)

***Dataset-2***: has  6 columns and 43K rows. Basic aggregate numbers covering 1979-2016, by country, year, age groups 
and sex based on WHO Mortality Database online tool.
[Here](https://www.kaggle.com/szamil/who-suicide-statistics) 

***Dataset-3***: with 8 columns and 2000 rows. This dataset contains suicide death counts by region, race or ethnicity, 
sex, and age group. For more information, check out: http://www.health.ny.gov/statistics/vital_statistics/.
[Here](https://healthdata.gov/dataset/vital-statistics-suicide-deaths-age-group-raceethnicity-resident-county-region-and-gender) 

#### Prerequisites/Installations:
1. ggplot2 
2. knitr  
3. ggm
4. car, QuantPsyc


GitHub repository can be found here: [GitHub](https://github.com/BhushanGitHub/bhushanGitHub.github.io/tree/main/Projects/suicide_rate_analysis)
