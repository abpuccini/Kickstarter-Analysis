# Kickstarter Project Analysis

## Background

Kickstarter, founded in April 2009, is a platform that gives an opportunity for people who have an idea of creative work and get the community to support them. Over $2 million and million people have been involved in campaign funding. However, not all of the campaigns launched on this platform are successful. Only one third of more than 300,000 projects launched on Kickstarter have reached their goal. Therefore, the analysis will be focused on a database of 4,000 past projects in order to uncover any hidden trends.

## Analysis

Here is the data sheets and figures to conduct the Kickstarter analysis. [Click here to Download Analysis Table](https://github.com/abpuccini/Kickstarter-Analysis/raw/master/KickstarterTableAnalysis.xlsx)

![KickstarterTableAnalysis](Images/KickstarterTableAnalysis.png)

## Conclusions

The conclusions will be conducted based on the Kickstarter campaign data collected from 2009 to 2017.

![StateperCategory](Images/StateCategory.png)

Regarding State per Category Chart, the majority of the campaigns is in the theater business. Also, the highest number of success is in the theater business as well.

![StateperSubCategory](Images/StateSubCategory.png)

Regarding State per Sub-Category chart, “plays” is the most successful sub-category campaign compared to others.

![StateperMonth](Images/StateTimeCreation.png)

Regarding State by Month from all those years, the highest number of successful campaigns takes place in May.

## Limitations

1. There are approximately 4,000 projects in the dataset which might be inadequate to represent all the Kickstarter projects which is 300,000 projects. That might mislead the conclusions of this analysis. The more accurate analysis might require a larger size of dataset. 
2.	In 2009 and 2017, the dataset does not contain a full year data. That could lead to misinterpret trends or forecasting.
3.	The goal, created date and ended date of each campaign are different which makes it difficult to standardize the analysis of the entire dataset. That might lead to a generalization.  
4.	The number of projects launched each year is different. In order to have a more accurate analysis, the dataset might be required to exclude any year that has a significant difference of launched project number.

## Other tables and graphs

### Predict Trend by Category

Creating a pivot table with a column of *state*, row of *year*, value based on the count of *state* and filters based on *Parent-Category* 

Also, creating a line chart linked with the pivot table to analyze trend of successful and failure by filtering *Parent-Category*.

This table and graph will conduct the trend of success and fail for each category from 2009 to 2017.

![CategoryTrend](Images/TrendCategory.png)

### Analysis of state by Parent and Sub category for each country

Creating a pivot table with a column of *state*, row of *country*, value based on the count of *state* and filters based on *Parent-Category* and *Sub-category*.

Also, creating a stacked chart linked with the pivot table to analyze which campaigns in which country tend to be more successful or failed by filtering *Parent-Category* and *Sub-category*.

This table and graph will conduct which campaign will be more interesting compared to others in each country.

![byCountry](Images/StateCountry.png)

### Analysis of backers’ interests toward the campaign category

Creating a pivot table with a row of *Sub-category*, value based on the sum of *backer* and filters based on *Parent-Category*, *year* and *state*.

Also, creating a column chart linked with the pivot table to analyze which campaigns tend to be more interesting for the backers by filtering *Parent-Category* and *year.

This table and graph will conduct which campaign (sub-category) will draw more backer’s attention than the others in order to be successful.

![BackerInterest](Images/SubCatBacker.png)

- - - 

## Statistical Analysis