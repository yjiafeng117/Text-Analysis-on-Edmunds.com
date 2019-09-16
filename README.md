# Text Data Analysis on Edmunds.com

Project from class User Generated Content Analytics.

Goals: As an analytics consultant to a (i) brand manager, (ii) product manager and (iii) advertising manager, the job is to give advice/insights to these individuals based on the analysis of social media conversations. Use cars as an example of a “high involvement” good (people use social media heavily for awareness building and research), look at the car review from site Edmunds.com to derive insights and generate recommendations.


## Data

Messages posted in Edmunds.com discussion forums.

Steps:

1. Develop a crawler/scraper using Selenium to fetch messages posted in Edmunds.com discussion forums. The crawler output should be a .csv file with the following columns: date, userid, and message.  

2. Fetch around 4,000 most recent posts about cars from a General topics forum. Do NOT choose a forum dedicated to a particular brand or model. Instead, choose the General & Sedans categories and then select, for example, the Entry Level Luxury forum https://forums.edmunds.com/discussion/2864/general/x/entry-level-luxury-performance-sedans
The idea is to have multiple brands and models being discussed without one of them being the focal point. 

3. Once fetch the data, find the top 10 brands from frequency counts. Write a script to count the frequencies. Replace frequently occurring car models with brands so that from now on you have to deal with only brands and not models. A list of model and brand names (not exhaustive) are provided in a separate file.   


## Tasks completed:

1. Identify top 10 brands by frequency, then find insights from analysis.

2. Find 5 most frequently mentioned attributes of cars in the discussions. Then pick the 5 most frequently mentioned brands and research on which attributes are most strongly associated with these 5 brands.

3. Find the most aspirational brand in the data in terms of people actually wanting to buy or own.

