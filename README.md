# BAN500_DescriptiveAnalytics
UNCW BAN500 Descriptive Analytics Final Project

To view, please download the xlxs file.

This goal of this final project was to independently choose a raw dataset to clean and analyze. 

As Emergency Medical Service (EMS) was a huge part of my life I decided to use response emergency response data from Tempe, Arizona for the years 2020-2021. I used 2020 as the COVID-19 pandemic was in full-swing, impacting every part of life, especially EMS response times and number of responses.

When looking at the ALS response data for Tempe, AZ in 2020 I want to answer these questions:
1.	Is there a particular time of day that is busiest? Day of week? Week of month?
2.	Does the time-of-day influence response times?
3.	What unit number responds to the most calls? By week and month.

Step one was cleaning up the data, removing any missing data or duplicates, separating date and time into separate columns, and standardizing those dates and times.
Next, I create a calculated column displaying the response time (how long it took for units to arrive).
I grouped the date related (Month, week, day of week) pivot tables and the time relate (time of day, response times) pivot tables I created. 
Finally I created a dashboard where users could focus in on specific EMS units, months of year, days, or even days of the week for different graphs. 
