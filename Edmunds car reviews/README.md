## Objective
As an Analytics consultant, to give advice/insights to the brand managers, product managers and advertising managers based on the analysis of social media conversations about cars.

## Approach:
1.	Using Selenium, fetch messages posted in Edmunds.com discussion forums. The crawler output will be a .csv file with the following columns: date, userid, and message. 

2.	 To fetch user written contents about cars from a General topics forum. The idea is to have multiple brands and models being discussed without one of them being the focal point. 

3.	After getting the data, we will identify the top 10 brands from frequency counts (stopwords excluded). Also, will replace frequently occurring car models with brands

4.	From the posts related to the top 10 brands, we will calculate the lift ratios for association. Will use a multi-dimensional scaling (MDS) map to visually represent the relation. 

## Key questions to answer:
1.	What are 5 most frequently mentioned attributes of cars in the discussions? The same attribute may be described by different words – e.g., pick-up and acceleration may both refer to a more general attribute, “performance”. 
2.	Find out the most aspirational brand in the data in terms of people actually wanting to buy or own. 
3.	What insights can be offered to brand managers from the analysis?
