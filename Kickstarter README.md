# Kickstarting with Excel

## Overview of Project
Use Excel to perform various skills aquired in Module 1 exercises and apply to a real-world problem to solve and report results. Louise has gathered much data for past Kickstarter campaigns and has asked me to derive information based on this sample size. They had origianlly worked with me for help in understanding if the goal for over $10,000 was reasonable for success so she could get funding to put on a play titles "Fever". In the end, they reached their goal before the campaign's end date. Now she would like me to see how other plays with similar goals measured in comparrison to theirs.

### Purpose
To assist Louise in understanding how launch date and/or funding goals could possibly contribute to successful campaigns using pivot tables, percentage tables, and vizualizations to help analyze Louise success to others with similar goals.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
![Image 1](Theater_Outcomes_vs_Launch.png)
[Image 1]
Assuming Louise launched their campaign in May and looking at our sample size of theater campaigns we can observe the following:
- 166 theater campaigns launched in May in outher years: 111 successful, 52 failed, and 3 canceled. 
- May was also the month with the largest amount of theater campaigns launched in a month with June closely behind. 
- The success percentage of theater campaigns for the month of May was the highest at 67%. 
- December had the lowest success rate at 49%.

### Analysis of Outcomes Based on Goals
![Image 2](Outcomes_vs_Goals.png)
[Image 2]
Assuming Lousie's goal was between $10,000 and $14,999, as well as, looking at our sample size of play campaigns we can observe the following:
- Play campaigns with a goal between $10,000 and $14,999 were 95% successful, 5% failed, and 0% cancelled.
- Play campaigns with higher goals had 100% success: $15,000 to $19,999 ; $25,000 to $29,999.
- Play campaigns asking for more than $45,000 had very low to no success.
- No Play campaigns were canceled

### Challenges and Difficulties Encountered
The only challenge I faced on this data report was remembering that the plays were to be taken into account when creating the formula for outcomes based on Goals. I reached out to my fellow classmates through Slack and Somin Kim replied to my question and mentioned I might be mising the subcategory. After that, all data ran correctly.

## Results
- What are two conclusions you can draw about the Outcomes based on Launch Date?
    - The months May and June are the best months to launch a theater campaign. From [Image 1] you can see that may and June have the highest number of successful theater campaigns, but they also have simarlly comparable failed campaigns which makes the success percentages for May and June, 67% and 75%, respectivly.
    - December is the month with the lowest success rate of 49%. One could argue this information makes it the worst month to start a theater campaign. You can see this in [Image 1] where the number of failed campaigns is almost equal to the number of sucessful campaigns.
- What can you conclude about the Outcomes based on Goals?
    - Louise had a goal amount bewtween $10,000 and $14,000. From the graph in [Image 2], you can see a large percentage of plays that ask for similar amount have a very high success rate. Even though the graph does demonstrate campaigns with a goal of more money (ie. $15,000 to $19,999; $25,000 to $29,999) had higher percentages of success, the number off success cases was more than 3 or more times higher in the $10,000 to $14,999 and failed numbers were very close in comparison to the other categories with higher success percentages. 
- What are some limitations of this dataset?
    One limitation of this dataset is that it is based on old data. The data set only goes to 2017 and trends may have changed 4-5 years that have passed. Another limitation of this dataset is that it is a closed set, we may have a more accurate analysis if we had a continous dataset or larger dataset.
- What are some other possible tables and/or graphs that we could create?
     We could create a table and a graph to answer the following questions:
        - What is the trend of theater campaigns by year? 
            We can create a copy of the "Theater Outcomes by Launch Date" sheet and edit the PivotTable Fields so Date created is removed in Rows and years is in rows only.
        - Are success' in May the same from year to year?
            We can view this by using the filter feature we created in the "Theater Outcomes by Launch Date" sheet and select various years