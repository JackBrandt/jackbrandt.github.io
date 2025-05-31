---
layout: post
title:  "Data Cleaning and Exploration"
date:   2025-05-29
categories: vbc
tag: data exploration
tag: data cleaning
---
**Data Cleaning**\\
Starting with over 70 data files, some with over 400,000 rows, it was important to start by eliminating unnecessary or unhelpful data. Since I plan to do this project by comparing hospitals to their neighbors, many datasets relating to state or national averages were deleted. Additionally, datasets with large amounts of missing values were deleted. This brought me done to 18 csv files to work with. Of the remaining datasets, unhelpful columns were removed to improve focus. The two main parts remaining for data cleaning is to address null or missing values, of which there are lots, and to join all of the data on the hospital attribute.\\
**Before Filtering**\\
<img src="/assets/images/raw_data_pic.png" alt="Profile Pic" width="800">

**After Filtering**\\
<img src="/assets/images/reduced_data_pic.png" alt="Profile Pic" width="450">

**Data Exploration**\\
While data cleaning was the focus of today's work, flipping through all of the data gave me some ideas for this project. Because there are so many attributes and because it's not clear which of them are most important, this project belongs to the realm of unsupervised statistical learning. Likely the first steps of data exploration will be to do primary component analysis with the goal of creating a handful of components that explain variability in quality of care, customer satisfaction, and price. Then, with these explanatory variables in hand, I can cluster hospitals by location to determine which of them should be recommended/covered.