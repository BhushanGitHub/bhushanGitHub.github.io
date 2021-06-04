---
title: ":broken_heart: Heart Failure EDA"
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
  <img width="460" height="300" src="/assets/images/heart_failure.jpg">
</p>


## Heart Failure EDA
<p align='justify'>

***Statistical/Hypothetical Question***

Cardiovascular diseases (CVDs) are the number 1 cause of death globally, taking an estimated 17.9 million lives each year, 
which accounts for 31% of all deaths worldwide.

Heart failure is a common event caused by CVDs and this dataset contains 12 features that can be used to predict mortality by heart failure.

Most cardiovascular diseases can be prevented by addressing behavioral risk factors such as tobacco use, unhealthy diet 
and obesity, physical inactivity, and harmful use of alcohol using population-wide strategies.

People with cardiovascular disease or who are at high cardiovascular risk (due to the presence of one or more risk factors 
such as hypertension, diabetes, hyperlipidemia or already established disease) need early detection and management wherein a 
machine-learning model can be of great help.

My hypothesis for this study was - 
H1 = Ejection fraction impacts Heart Failure. 
H0 = There is no effect of Ejection fraction on heart failure. 

There was 299 observation in the dataset. The independent variables in the dataset are - 
age, anaemia, creatinine_phosphokinase, diabetes, ejection_fraction, high_blood_pressure, platelets, serum_creatinine, 
serum_sodium, sex, smoking, time and dependent variable DEATH_EVENT. I used ejection fraction for analyzing the impact on death events.
It has been observed in the EDA analysis that Ejection fraction with a p-value less than the significance level of 0.05. 
This means Ejection fraction has an impact on heart failure. Hence we reject null hypothesis H0. 

</p>  

#### DataSets:

[Heart Failure Data](https://www.kaggle.com/andrewmvd/heart-failure-clinical-data)

#### Prerequisites/Installations:
- Python 3
- Pandas
- Numpy


GitHub repository can be found here: [GitHub](https://github.com/BhushanGitHub/bhushanGitHub.github.io/tree/main/Projects/heart_failure)
