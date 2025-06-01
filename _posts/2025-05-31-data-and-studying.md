---
layout: post
title:  "Data and Studying"
date:   2025-05-29
categories: vbc fam
tag: data exploration
tag: data cleaning
tag: studying
tag: pivot tables
---
**Data**\\
I continued with the data cleaning and exploration. I have finished half of the joining of the datasets. This process has required the data to be even further paired done, but also better formatted. For example, Some of the tables had hospitals in multiple rows, one for each of a variety of measures. So, I had make pivot tables with Python's Pandas's DataFrames to rearrange the data. This left some tables with over 80 columns, so I focused on extracting features that I thought summerized a table when possible. For example, with the survey data there were dozens of measures for all the questions and response levels, but for simplicity only the overall customer rating was kept. Without feature reduction of this manner, there would be hundreds (if not thousands) of variables at the end. This would make identifying the important ones almost impossible. While I do currently intend to do PCA anyway, I believe PCA will provide more helpful results if I start it off with only the most relevant data to begin with. Hopefully, I can finish this process of data cleaning in the next few days. All I have left is to finish joining the data and figure out what to do with all of the missing values.

**Studying**\\
As it's been one week since taking and passing exam SRM, my break/rest period is over and now it is time to begin studying for my next exam: FAM. I've heard FAM covers a lot of material so I'll be taking the sitting in October instead of the one in July, giving me 5 months to study instead of 1.5. I'm excited for this one as it is literally foundations of actuarial mathematics which leads me to believe it will be more closely related to actuarial work than the past few.