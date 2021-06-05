---
title: "Amazon Product Review Rating Insights"
layout: post
tag: 
- Data Analysis 
- python
- Data Mining

headerImage: true
projects: true
hidden: true # don't count this post in blog pagination
description: " "
image: "/assets/images/amazon_prod_review.png"
category: projects
author: Bhushan Suryawanshi 
externalLink: false
---


<p align="center">
  <img width="460" height="300" src="/assets/images/amazon_prod_review.png">
</p>


## Amazon Product Review Rating Insights
<p align='justify'>

With the e-commerce boom, there are multiple products available to consumers. While deciding the best product as well as 
recommending products for the user e-commerce enterprises rely on the product review. Having these product review data 
in good quality will also help analytic teams to come up with a better model. I am using amazon product reviews for the 
analysis. I will be using existing reviews to find the review rating based on the text. The review rating ranges from 1 
to 5, where 1 is the lowest, and 5 is the max rating. For example, if the review contains the text “Good product to be 
used.” The model will try to see what can be the review rating for this review. This will help improve the quality of 
data by detecting review ratings based on review text if it is missing. As well as ensure that the review ratings are in 
compliant with review text.

</p>  

#### DataSets:

The dataset is a list of consumer reviews for multiple products. There are a lot of details in this dataset but I will 
be using - name, primaryCategories, manufacturer, reviews.doRecommend, reviews.rating, and reviews.text for my analysis.

Amazon Product review Dataset - [Click Here](https://www.kaggle.com/datafiniti/consumer-reviews-of-amazon-products)

#### Prerequisites/Installations:
- Python 3
- Pandas
- Numpy
- sklearn


GitHub repository can be found here: [GitHub](https://github.com/BhushanGitHub/bhushanGitHub.github.io/tree/main/Projects/amazon_product_review)  
