# Surfs Up Challenge – 
## Overview of Project
The challenge involved providing a potential investor with requested information on a business venture. 
The investor required running some analytics on a weather dataset. I used SQLite, SQLAlchemy, Flask & 
Python to develop these analytics.


## Project Steps
The investor requested information about temperature trends before opening the venture. Specifically, 
he requested multitemperature data for the months of June and December in Oahu, HI in order to 
determine if the surf and ice cream shop business is sustainable year-round. The project consisted of 
two technical analysis deliverables: (1) the June historical weather summary statistics and (2) the 
December historical weather summary statistics. To complete these I used Python, Pandas functions and 
methods, and SQLAlchemy to filter the date column of the measurements table in the hawaii.sqlite 
database to retrieve all the temperatures for the month of June and December. I then converted those 
temperatures to respective lists, created DataFrames from each list, and generated the summary 
statistics from each dataframe. </p>






### Key Differences in Weather Between June and December
There are three key differences in the weather between June and December:
*	June has higher temperatures than December, 3.9 degrees using the average and 4.0 degrees using 
	the median.
*	June has much higher minimum temperature than December, 8.0 degrees higher, but only 2.0 degrees 
	higher for the maximum temperature.
*	June has a lower standard deviation, 3.26, than December, 3.75. </p>

![image](https://user-images.githubusercontent.com/100445489/165592498-a8b50a9a-5031-42ed-a7e3-c047376aa183.png)

![image](https://user-images.githubusercontent.com/100445489/165592536-af8a17bb-3259-447e-955e-ff6c7a0e62f7.png)




## Summary
The Oahu, HI weather analysis indicates that June has higher temperatures than December as measured 
by the mean, median, minimum and maximum temperatures. Also, June temperatures have a lower standard 
deviation than December temperatures. That is, June temperatures are more clustered around June’s 
mean temperature than December temperatures are around its respective mean.  </p>
