# Kickstarter_analysis1CA

## Overview of Project
Lousie wants to know how successful her other theater, specifically plays, did in relation to time of the year and the percentage of successful, failed and canceled campaigns.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date 
Pulling information from the kickstarter I created a line graph that clearly shows that the most successful months of compaigns were during the spring/summer months. During these months the outcomes were more likely to be successful with less failed campaigns then during the winter months. The most successful month being May with 111 successful theater campaigns that either reached their goal or exceeded it. While December was the least successful campaign month with only 37 successful theater campagins and 35 failed ones. [github pages](resources/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals 
Using the Countifs function I was able to determine the percentage of successful, failed and canceled campaigns over the course of 7 year (2010 to 2017). By creating a line graph we can see that campagins whose goals were $24999 or less were more likely to be sucessful. The most successful campaign was when goals were less $1000, with a total of 186 projects 76% of them were suceesful. Projects with a goal of $40000 were more likely to fail, between $40000 to $49000 100% of projects failed and projects with a goal of $50000 failed 83% during the 7 years this data was collected. 
[github pages](resources/Outcomes based on goals.png)

### Challenges and Difficulties Encountered
Some Challeges I faced while coverting the date from linus to human date and creating the years colums was somehow empty data cells were created. When I created my pivot table and turned that in to a line graph I had a fifth line on my line graph. To fix it I went back to my original kickstarter datasheet and had to re-calculate the human date and year columns. using the countifs was tricky, my outcomes based on goals graph was showing data out of order and i had to manually move the goal column amount to their correct place (least to greatest). Also one of the values in the counifs function was incorrect throwing off all the values. I went row by row correcting the incorrect variable.  

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date? Plays launched in the summer/spring months had a greater chance of success than plays launched during the winter months. Months April, May, June, July and August had the most successful outcomes, May being the most successful with 111 successful projects. It seems based on from the data provided from Kickstarter backers were likely to donate during the spring and summmer months regardless of country. Its possible that during the winter months they are less likely to donate because its the holiday season. 
- What can you conclude about the Outcomes based on Goals? the larger the campaign goal the less likely the project will recieve enough donations. Donations of $35000 to $39999 and $40000 to $44999 being the outliers, those goals only had a total of 9 projects with a 67% success respectively. 
- What are some limitations of this dataset? the only data that we have taken into consideration is the date the campaign launched and teh percentage of successful, failed and canceled campaigns depending the dollar amount of the gaol. We haven't considered the amount of backers each play had. Successful projects had a total of 413 backer while failed projects only had 251 backers. Why is that? Did Lousie fundraise harder for certain projects over others? Was there more opportunity to raise mony for the campaign during the summer and spring months? Was each campaign for the eaqual amount of time? I think that more context is needed to be able to draw better conclusions as to why certain projects did better then others.
- What are some other possible tables and/or graphs that we could create? I would love to table/graph that included both the outcomes based on date and how much money was raised. Another would be how long they raised money for each project and how much money was raised. 
