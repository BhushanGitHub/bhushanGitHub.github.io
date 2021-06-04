---
title: "Wine Quality Prediction"
layout: post
tag: 
- Data Preperation 
- python
- Data Analysis


headerImage: true
projects: true
hidden: true # don't count this post in blog pagination
description: " "
category: projects
author: Bhushan Suryawanshi 
externalLink: false
---

<p align="center">
  <img width="460" height="300" src="/assets/images/wine_quality.jpg">
</p>


## Wine Quality Prediction
<p align='justify'>

Today, if you walk into a wine shop there are about 100 different wine bottles on display. How to choose the one with good quality. To get quality wine either you need to be an expert wine taster or you need to follow one of them to get the list of good quality wine. 
Having data in hand and using that data for knowing the quality of wine will help democratize this space. Hence, conducted a study learning different chemicals available in wine to decide the quality of the wine. 
The study involves 1600 different observations across 12 features. The dataset was made available at both Kaggle and UCI machine learning repository. Having limited knowledge of different chemicals other than alcohol made it challenging. However, techniques such as finding feature importance and feature selection helped in identifying top influencing features for the model. Also, the target feature had imbalanced data and had to use the re-sampling technique to have uniform sampling across different categories of wine. 
Since this is a multi-class classification problem, used algorithms like logistic regression, KNN and also studied the impact of using neural network. The study shows that KNN worked the best with N=5 and balanced classes giving an accuracy of 82% on the test data. 

</p>  


#### DataSets:


The dataset is containing 1600 different observations of wine samples. It consists of 12 features with one of them being our target variable “quality”. The features are the chemical properties of wine. These physicochemical properties can be used with machine learning techniques to classify good or bad quality wine. The quality feature showing value more than 6.5 is good quality wine and anything below 6.5 is low/bad quality wine. 
The other features in the data set are -

- fixed_acidity
- volatile_acidity
- citric_acid
- residual_sugar
- chlorides
- free_sulfur_dioxide
- total_sulfur_dioxide
- density
- pH
- sulphates
- alcohol 


[Kaggle Wine_Quality Dataset](https://www.kaggle.com/uciml/red-wine-quality-cortez-et-al-2009)


#### Prerequisites/Installations:
- Python 3
- Pandas
- Keras


GitHub repository can be found here: [GitHub](https://github.com/BhushanGitHub/bhushanGitHub.github.io)  
