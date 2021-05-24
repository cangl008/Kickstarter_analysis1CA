# Kickstarter_analysis1CA

## Overview of Project
Lousie wants to know how successful her other theater, specifically plays, did in relation to time of the year and the percentage of successful, failed and canceled campaigns.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date 
Pulling information from the kickstarter I created a line graph that clearly shows that the most successful months of compaigns were during teh sprin/summer months. During thise months the outcomes were more likely to be successful with less failed campaigns then during the winter months. The most successful month being May with 111 successful theater campaigns that either reached their goal or exceeded. While December was the least successful campaign month with only 37 successful theater campagins and 35 failed ones. [github pages](resources/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals 
Using the Countifs function I was able to determine the percentage of successful, failed and canceled campaigns over the course of 7 year (2010 to 2017). By creating a line graph we can see that campagins whose gaols were 24999 or less were more likely to be sucessful. The most successful campaign was when goals were less $1000, with a total of 186 projects 76% of them were suceesful. Projects with a goal of $40000 were more like to fail, between $40000 to $49000 100% of projects failed and projects with a goal of $50000 failed 83% during the 7 years this data was collected. 
[github pages](resources/Outcomes based on goals.png)

### Challenges and Difficulties Encountered
Some Challeges I faced while coverting the date from linus to human date and creating the years colums was somehow empty data cells were created. When I created my pivot table and turned that in to a line graph I had a fifth line on my line graph. To fix it I went back to my original kickstarter datasheet and had to re-calculate the human date and year columns. using the countifs was tricky, my outcomes based on goals graph was showing data out of order and i had to manually move the goal column amount to their correct place (least to greatest). Also one of the values in the counifs function was incorrect throwing off all the values. I went row by row correcting the incorrect variable.  

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date? Plays launched in the summer/spring months had a greater chance of success than plays launched during the winter months. Months April, May, June, July and August had the most successful outcomes, May being the most successful with 111 successful projects. It seems based on from the data provided from Kickstarter backers were likely to donate during the spring and summmer months regardless of country. Its possible that during the winter months they are less likely to donate because its the holiday season. 
- What can you conclude about the Outcomes based on Goals? the larger the campaign goal the less likely the project will recieve enough donations. Donations of $35000 to $39999 and $40000 to $44999 being the outliers, those goals only had a total of 9 projects with a 67% success respectively. 
