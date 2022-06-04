# Video-Games-Sales-Analysis
## Executive Summary
Because of the dynamicity in video game industry, the video games sales dataset has been analyzed by transforming and visualizing the data, which will be beneficial in improving both sales and customer satisfaction. Also, the analysis will be useful in addressing the plans for improving the next version of the games.

## Introduction about the Industry
Video games have been around for decades, providing entertainment for both children and adults. They have evolved significantly since the early days of computer games. Pixelated screens and limited sound are a thing of the past, as video games have become more lifelike than ever.
As technology advances, so do video games. The video game sector is immensely large and is growing fast. In 2021, the gaming industry generated total revenue of $178.73 Billion. Tech giants like Google, Meta, and Apple have all made plans to enter the gaming industry and generate more revenue. Subscription streaming services are the future and will be beneficial to video game companies. Technical innovations, expanding market demographics, and an increase in video game-related merchandise have all contributed to the video game industry's new scope.

## Problem
Video games are a billion-dollar business and have been for many years. The vast growth of gaming industries attracts many companies, but lack of knowledge about the games trend and design makes it difficult for companies to understand the demand of customers and therefore restrict them to enter the video game industry.

## Solution/Objective
Our objective is to analyze the sales trend of video games in different countries for various platforms, to track trends, and diagnose problems to find solutions that can help the companies understand the demand of the customers.

## Description about Datasets
There were 6 csv and 2 excel files, that contained the data about sales of different platform games in 3 different regions (North America, Japan, and Europe), along with sales in rest of the world. There were total of 11 variables (Rank, Name of Game, Year of game developed, Genre, Platform, Publisher, Sales in North America, Japan, Europe, Other regions, and Global sales).

## Data Preparation
Before merging the datasets into master dataset, data was prepared by renaming columns, delete irrelevant column like “Rank”, creating new columns, and reordering columns for consistency. After processing the datafiles, they were merged to obtain 16600 observations and 10 columns.

## Data Cleaning
For data cleaning, 3 duplicated values, 2 outliers, and 0.35% rows with missing values in column “Publisher”, were removed. Missing values in column “Year” were replaced with its median and in Sales columns were replaced using the formula:
Global Sales = Sales in (North America + Japan + Europe + Other Regions)
Normality was also checked by categorizing the companies into big and small companies, but as sales were in genuine range, the normality remained the same.
After cleaning the data, the final cleaned dataset had 16537 observations and 10 columns.

## More about data
*	It has been found that games’ names were all unique and acted as primary key in our dataset. Also, only 8 platforms (PS2, DS, PS3, Wii, X360, PSP, PS, PC) were un-rare and their proportion is 70% and among all the years only 8 years (2007, 2009, 2008, 2010, 2011, 2006, 2005, 2002) were un-rare and repeated many times in the dataset. It means that most of the data observations densely concentrate on these few labels (8 for Platform and 8 for Year).
* There was a strong correlation between sales in North America and Global Sales, indicating that North America was the greatest contributor in Global Sales.
* From chi-square, the Genre and Platform observed to be associated with each other.

## Valuable Information
From the dashboard and the analysis in Python, the following information was obtained:
* Total sales of video games worldwide from 1998 to 2020 was $ 8.91K Millions.
* North America ranked first in terms of video games sales with a proportion of 48.16%, while Europe ranked second with 28.15%
* The golden years, when sales were maximum, were 2007, 1998 and 2011 for North America, Europe, and Japan respectively.
* From 1998 to 2020, the top 4 genres were Action, Sports, Shooter, and Role-Playing. 
* From 1998 to 2020, Action was the most favourite Genre in North America, Europe, and other regions, however, from the last decade, the genre ‘Shooter’ was the most popular one in North America, Japan, and other regions.
* Among the most popular genres, Action and Shooter, the most sellable games were ‘Grand Theft Auto V’ and ‘Wii Sports’ respectively. 
* In the period of 22 years, the most popular platforms were PS2, PS3 and X360. However, when new consoles were developed, then in the last decade the popularity of PS4 also increased.
* Among the top publishers, Nintendo, Electronic Arts, Activison, and Sony Computer Entertainments were on the top. 
* However, these top publishers were more focused in Sports games, while in Action genre they were not on the top list.
* The bottom 5 genres include strategy, adventure, puzzle, fighting and simulation. While platforms like Dc, WS, N64 and publishers like Boost On, and Ascaron Entertainment were the least popular with around $0.01 Million sales worldwide.
Conclusion and Recommendation
From our analysis about sales in video games, the following includes the conclusion and recommendations:
* To start a business in video gaming industry, one should target the video game loveable regions like North America and Europe.
* PlayStations are one the most popular platforms, so similar gaming platforms should be developed.
* More focus should be given on Action and Sports games, as they were the most popular genres.
* For the organization who are already in this industry, the most popular publishers like Nintendo, Electronic Arts and Sony Entertainment, should focus more on developing action games, to increase their sales.
Not everyone has a similar taste in video games, but these results will be beneficial for the businesspersons in improving both sales and customer satisfaction. Also, the analysis will be useful in addressing the plans for improving the next version of the game.

