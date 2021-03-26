---
title: ":canada: Toronto Crime Relationships"
layout: post
date: 2020-05-30 10:00
tag: 
- visualizations
- python
- folium
headerImage: true
projects: true
hidden: true # don't count this post in blog pagination
description: " - A report focused on reviewing multiple sources, by different means, to determine various relationships within Toronto."
category: projects
author: bhushans
externalLink: false
---

![Screenshot](/assets/images/toronto.jpg)

## Toronto Crime Relationships   

<p align="justify">A report gathering and reviewing multiple sources, by different means, to determine various relationships within Toronto.</p>  

## Data - Sources and Descriptions  

[Toronto Neighborhood Profiles](https://open.toronto.ca/dataset/neighbourhood-profiles/)  

<p align="justify">The Census of Population is held across Canada every five (5) years and collects data about age and sex, families and households, language, immigration and internal migration, ethnocultural diversity, Aboriginal peoples, housing, education, income, and labor. City of Toronto Neighborhood Profiles use this Census data to provide a portrait of the demographic, social and economic characteristics of the people and households in each City of Toronto neighborhood. The profiles present selected highlights from the data, but these accompanying data files provide the full data set assembled for each neighborhood. Each data point in this file is presented for the City's 140 neighborhoods, as well as for the City of Toronto as a whole. The data is sourced from a number of Census tables released by Statistics Canada. The general Census Profile is the main source table for this data, but other Census tables have also been used to provide additional information. Additional information can be found <a href='https://www.toronto.ca/city-government/data-research-maps/neighbourhoods-communities/neighbourhood-profiles/'>here</a>.</p>  

[Neighborhood Crime Rate (Boundary File)](https://data.torontopolice.on.ca/datasets/af500b5abb7240399853b35a2362d0c0_0?geometry=-80.685%2C43.542%2C-78.072%2C43.890)  

<p align="justify">Toronto Neighborhoods Boundary File includes 2014-2018 Crime Data by Neighborhood. Counts are available for Assault, Auto Theft, Break and Enter, Robbery, Theft Over and Homicide. Data also includes four-year averages and crime rates per 100,000 people by neighborhood based on 2016 Census Population.</p>  

[Narcity News Article on Toronto Crime Rates](https://www.narcity.com/ca/on/toronto/news/toronto-neighbourhoods-ranked-by-how-dangerous-they-are-right-now-based-on-2018-crime-rates)  
<p align="justify">This article provides a breakdown of the most common crime occurrence in each neighborhood, as well as the police district the neighborhood resides. This was one of the few sources providing the neighborhoods tied to their districts.</p>  

<p align="justify">With these three datasets, there are 140 variables (each neighborhood) and approximately 2400 rows across them.</p>  

## Relationships

<p align="justify">The common relationship running through all three data sets is the neighborhood id (name). This one to many relationship occurs on with each. With this common relationship, there is belief that patterns will emerge across each neighborhood pertaining to crime and different demographics.</p>  
 
GitHub repository can be found here: [GitHub](https://github.com/BhushanGitHub/Toronto_Crime_Relationships)   
The final results can be found here: [Final Results](https://github.com/BhushanGitHub/Toronto_Crime_Relationships/blob/master/Code/Bhushan_Suryawanshi_Milestone_5.ipynb)
