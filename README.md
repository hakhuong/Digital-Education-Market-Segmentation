# Oppia Growth Analytics: Country Segmentation for Digital Outreach

## Related documents
+ Data Studio report to visualize results of clustering: https://datastudio.google.com/reporting/579277e7-6456-4ac4-b1ec-37c85020d46c 
+ Full report: https://docs.google.com/document/d/1aQyoRg9xto3oIQy1jX7UmZOEvSL9lb67nYQuRP78Wvo/edit?usp=sharing
+ Jupyter Notebook - Data cleaning, Data exploration, and Clustering
+ Data source: The Global Competitiveness Report 2017-2018 http://reports.weforum.org/global-competitiveness-index-2017-2018/

## TL;DR
This project used a hierarchical clustering technique to classify 134 countries into 3 segments: 1) High education quality - Good internet access 2) Low education quality - Moderate internet access and 3) Low education quality - Low internet access. I recommended targeting 66 countries in Group 2 for the highest impact from Oppia’s outreach effort. Next steps from this project can be combining this result with language data and with Oppia’s user traffic data. 

## Overview 
As Oppia is growing, exploring different geographic regions to identify areas of potential growth is necessary. Knowing where there may be the largest opportunity for impact, we can plan our digital outreach accordingly to maximize the return on resources investment. 

In this project, I identified the potential areas for outreach based on 2 criteria: education quality and internet access. As Oppia’s mission is to improve education quality for children around the world, Oppia can have the most impact when reaching out to areas where students are not provided with good education quality. At the same time, that country/region should have decent internet access since Oppia is a digital platform. Combining the 2 aspects, regions where Oppia might have the greatest impact are where having low education quality and moderate level of internet access.

## Result

The best result I selected has 3 clusters with a Silhouette score of 0.33.
More descriptive statistics of each cluster can be found in the jupyter notebook and the Data Studio report. 
![dendro](https://user-images.githubusercontent.com/45189309/91504497-27d6c300-e882-11ea-896b-78621de259c6.png)




