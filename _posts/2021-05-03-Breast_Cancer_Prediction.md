---
title: "Breast Cancer Prediction"
layout: post
tag: 
- Python
- Regression
- Model Comparison 

headerImage: true
projects: true
hidden: true # don't count this post in blog pagination
description: " "
image: "/assets/images/breastCancerTitle.png"
category: projects
author: Bhushan Suryawanshi 
externalLink: false
---

<p align="center">
  <img width="460" height="300" src="/assets/images/breastCancerTitle.png">
</p>

## Breast Cancer Prediction
<p align='justify'>

Lifetime breast cancer risk in U.S. women is 1 in 8 that is about 13%. In 2021 it is expected 
that the US will add 281,550 cases of breast cancer in women. If it can be detected and treated 
early, studies show that these statistics can be improved. The purpose of this project was to 
determine if machines can accurately assist doctors, particularly breast cancer specialists, in 
making an accurate predictive diagnosis relating to breast cancer. 
</p>

#### DataSets:

<p align='justify'>
Breast cancer testing has a process called Fine Needle Aspirate (FNA). This process uses breast mass collected using a hollow needle attached to a syringe to get a small amount of tissue. Which is used to run laboratory tests. The data is collected from these tests and made available for machine learning. This database is available through - 
</p>

[UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29)

[Kaggle - Breast Cancer Dataset](https://www.kaggle.com/uciml/breast-cancer-wisconsin-data)

Attribute Information:

1. ID number

2. Diagnosis (M = malignant, B = benign)

3. 3 to 32) Ten real-valued features are computed for each cell nucleus:

    - radius (mean of distances from center to points on the perimeter)
    - texture (standard deviation of gray-scale values)
    - perimeter
    - area
    - smoothness (local variation in radius lengths)
    - compactness (perimeter^2 / area - 1.0)
    - concavity (severity of concave portions of the contour)
    - concave points (number of concave portions of the contour)
    - symmetry
    - fractal dimension ("coastline approximation" - 1)

<p align='justify'>
The dataset also provides the mean, standard error, and "worst" or largest (mean of the three largest values) of these features for each image, resulting in 30 features. 
</p>

#### Prerequisites/Installations:
- Python 3
- Pandas
- Keras
- TensorFlow
- CNN

#### Analysis

<p align='justify'>
In this study, the data provided by the Diagnostic Wisconsin Breast Cancer database is used to 
analyze and run through four different predictive models. In order to accurately determine if 
the predictive model could make predictions, multiple characteristics were evaluated to 
determine their value in our formula. Since this is a classification prediction problem, 
the following models were selected for evaluation: Random Forest Classifier, Logistic Regression CV, K-Nearest Neighbor 
Classifier, and Support Vector Machines (SVM) with Support Vector Classifier. A simple function was created for 
displaying each model’s metrics. Each model was fit and tuned using the training data set, and a prediction was made 
and evaluated using the testing data. Models have been evaluated in Python and R. Each model was able to accurately 
predict a correct diagnosis of a cancerous tumor over 90% of the time. These results are very exciting and help in 
breast cancer diagnosis. 

Exploring the data has led to some basic and interesting discoveries. The data consists of 569 records, with 212 as 
malignant and 357 diagnosed as benign, 37.26% and 62.74% respectively.  
</p>


<img width="460" height="300" src="/assets/images/Bar%20Graph.jpg">


<p align='justify'>
With the pair plot, we are able to visualize initial patterns of how the features and diagnosis relate to one another. 
</p>


<img width="460" height="300" src="/assets/images/original%20data%20correlation.png">


<p align='justify'>
The following graph shows the distribution of data after log transformation. 
</p>


<img width="460" height="300" src="/assets/images/log_histogram.png">


<p align='justify'>
Feature selection was the most important and challenging portion of the analysis. With the data set being relatively 
small, 529 records, and many of the features having high correlations, it was vital to identify the most important 
features, but also not to eliminate those with minor significance.

The dataset was randomly split into 80% training and 20% testing data sets. Since this is a classification prediction problem, the following models were selected for evaluation: Random Forest Classifier, Logistic Regression CV, K-Nearest Neighbor Classifier, and Support Vector Machines (SVM) with Support Vector Classifier. For metrics visualization, a simple function was created that can be used with each model. Each model was fit and tuned using the training data set, and a prediction was made and evaluated using the training data. Models were evaluated in both Python and R.

Results: The results from each model are shared below. 
</p>


<img width="460" height="300" src="/assets/images/BreastCancerResults.jpg">
  

GitHub repository can be found here: [GitHub](https://github.com/BhushanGitHub/bhushanGitHub.github.io/tree/main/Projects/breast_cancer_prediction)  
