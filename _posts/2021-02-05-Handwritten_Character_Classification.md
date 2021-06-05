---
title: "Handwritten Character Classification"
layout: post
tag: 
- Python
- Deep Learning
- CNN

headerImage: true
projects: true
hidden: true # don't count this post in blog pagination
description: " "
image: "/assets/images/devnagari.png"
category: projects
author: Bhushan Suryawanshi 
externalLink: false
---

<p align="center">
  <img width="460" height="300" src="/assets/images/devnagari.png">
</p>

## Handwritten Character Classification
<p align='justify'>

Handwritten character recognition is an important part in computer vision domain. Handwritten character recognition is 
least explored for the Devnagari character (Indian Language). There are different techniques used in handwritten 
character recognition. Several researches have been done to develop a system which will provide a good accuracy. 
There are two techniques of character recognition system namely online and offline character recognition. 
Here we used offline handwritten character system. In offline character recognition system handwritten characters of 
user are available as image.   

Handwritten character recognition can benefit multiple industries. 

Some of those are -
***Consumer*** : With smartphone and tablets, consumer industry need something to minimize spelling mistakes on digital 
keyboards and handwritten character recognition can help in great way.

***Education***: Using handwritten technology, students can benefit from more than just the increased comprehension 
linked to taking handwritten notes. 

Handwritten technology is can be used in note taking, math and even music apps. For this character classification problem, 
the dataset used is having 78,200 images of 46 Devnagari characters. The data is split into training and testing set 
for model training and verification. Using current advancement in Deep learning using Convolutional Neural Network (CNN) 
helped to achieve greater accuracy. 

</p>  

#### DataSets:

UCI Machine Learning Repository [Here](https://archive.ics.uci.edu/ml/datasets/Devanagari+Handwritten+Character+Dataset)

This is an image database of Handwritten Devanagari characters. There are 46 classes of characters with 2000 examples each. 
The dataset is split into training set(85%) and testing set(15%).


#### Prerequisites/Installations:
- Python 3
- Pandas
- Numpy
- sklearn
- keras
- TensorFlow
- Anaconda


GitHub repository can be found here: [GitHub](https://github.com/BhushanGitHub/bhushanGitHub.github.io/tree/main/Projects/handwritten_character_classification)  
