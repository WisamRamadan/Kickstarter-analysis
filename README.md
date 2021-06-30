# Kickstarting with Excel
---
## Overview of Project
Data-driven decisions pave the way for success. In this project, quatitative analysis of Kickstarter campaigns is conducted to help Louise reach her play _Fever_ fundraising goal and define the best strategy to achieve it. The analysis illustrates the results of outcomes based on launch date and goals, describes challenges faced, and introduces conclusions and data limitations.
### Purpose
The purpose of this project is to perform analysis on Kickstarter data to uncover trends and insights related to plays in kickstarter campaigns.  

## Analysis and Challenges
The analysis included 1369 Theater campaigns in 21 countries. Theater campaigns outcomes' analysis revealed that the highest nymber of successful campaigns was for those launched in May then June. Slicing down to the subcategory of plays, analysis of outcomes based on goal showed that highest percentage(76%)of success was for campaigns with goal range less than 1000$. 

### Analysis of Outcomes Based on Launch Date

![Theater_Outcomes_vs_Launch](/resources/Theater_Outcomes_vs_Launch.png)

The graph shows the _Theater_ outcomes for each month. Successful campaigns peak in May (111) and hit its lowest value in December (37).  Failed campaigns tend to have a flat peak with close results for May, June, July, and August. Canceled campaigns show uniform low results over the year except for October with zero canceled campaigns.

### Analysis of Outcomes Based on Goals

![Outcomes_vs_Goals](/resources/Outcomes_vs_Goals.png)

The graph shows the _Plays_ outcomes vs goal range. The highest percentage of successful campaigns was 76% for the goal range of 1000$ or less. The lowest percentage of successful campaignes was 0% for the goal range 45,000 to 49,999$. 

### Challenges and Difficulties Encountered
The dataset for plays campaigns has significant number of outliers that may have skewed the results. Although grouping goals into ranges enhanced visibility of results, the trend generated was sufficient to explain success or failure rate based solely on goal.
Theater dataset has three subcategories which means that results shown can not be generalized on each subcategory. Conclusions can be made only about the parent category. A pivot chart would solve the issue as we can see the trend for each subcategory.

## Results

Two conclusions can be drawn about the Outcomes based on Launch Date analysis. First, Theater campaigns launched in May have the highest chance of success. Second, Theater campaigns launched in December have the lowest chance of success.

For the Outcomes based on Goals, we can conclude that Louise's play with a goal of 4000$ may have 73% chance of success as it falls under the goal range of 1000-4999$.   

However, there are some limitations of this dataset. First, there are gigantic outliers, campaigns with goals above 1000000$, that may affect the results. Second, this dataset includes data from 21 countries. This means that more variables should be considered to customize the dataset to Louise play's campaign launching country and goal. Benchmarking with similar campaigning conditions makes it easier to draw meaningful conclusions.

Other possible tables and graphs that we could create includes the following:
- Pivot table to show success rate per goal range and country filtered by Parent Category, Subcategory, and Years. 
- Box and Whisker chart to identify outliers
- Line chart for Outcomes Based on Launch Date for _plays_ subcategory

