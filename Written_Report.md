# Kickstarting with Excel

## Overview of Project
### Purpose
The purpose of this project is to understand how the campaigns that fell into the "theater" and "plays" category performed based on their launch dates and fundraising goals. The launch date analysis analyzed whether the a theater campaign was more successful based on what month it launched. The goal based analysis analyzed whether a goal was more successful based on the fundraising goal amount. 


## Analysis and Challenges
### Analysis of Outcomes Based on Launch Date
Based on the graph created in this analysis, a theater campaign has the highest chance of success when launched during the summer with the peak month being May. Fall and winter seem to be the least popular month for launch with the highest failure rate peaking in October and December. One could assume that this could be related to holiday season approaching. 
![Theater_Outcomes_vs_Launch](C:\Users\heeja\Desktop\julia's data bootcamp\module 1\Challenge\Resources\Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals
Based on this analysis, a play campaign is the most successful with smaller goal of less than $5,000 and a larger goal of $3,5000 to $4,5000. However, when a goal reaches above $4,5000 the success rate drops significantly. Additionally, the success/fail rate is around the same in the middle range of $5,000 to 2,5000
![Outcomes_vs_Goals](C:\Users\heeja\Desktop\julia's data bootcamp\module 1\Challenge\Resources\Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered
When analyzing the success rate based on the launch date, it was tricky to filter out the "live" campaign status. After playing around the pivot table by clicking all the arrows possible, I was able to understand all the filters I could use. It was interesting to see the difference in filtering the parent category and filtering the outcomes column. Additionally, although the graph was helpful in seeing how each outcome did throughout time, it would have been helpful to see a bar graph to see exactly how each status compared to each other and the total number of shows per month. In order to come to my final conclusion, I ended up finding the percentage of success and failure as well to see how it was exactly distributed.

When analyzing the outcome based on goals, it was challenging to successfully use the COUNTIFS function. After getting a few errors, I google searched for some examples. Unlike the IF function, I had to use quotation marks ("") to describe the parameters I was looking for. Reading through the examples online helped me quickly fill out my the table. 
[Kickstarter_Challenge_Final](C:\Users\heeja\Desktop\julia's data bootcamp\module 1\Kickstarter_Challenge_Final.xlxs).

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
When launching a theater campaign, plan to set a launch date for the summer, preferably in May. Also, avoid launching during the winter, especially during October - December. 

- What can you conclude about the Outcomes based on Goals?
A play campaign with a smaller goal of under $5,000 is much more successful than setting an unrealistic goal of above $45,000. If the play is of larger caliber, the best range to shoot for is $35,000 to $45,000

- What are some limitations of this dataset?
The dataset has 12 different types of currency. It is difficult to compare based on monetary goals because the difference in currency would mean the goals hold a different value based on the type of currency. Additionally, if launching in the US, it would have been helpful to understand which state each project was in. The interest in theater and plays could differ based on region. 


- What are some other possible tables and/or graphs that we could create?
In the 'Theater Outcomes by Launch Date' sheet, it would have been helpful to add a few columns to the pivot to understand the percentage of success, failure and cancellation; seeing this breakdown would have made it easier to see the ratio between success and fail. Additionally, adding a stacked bar graph would have made it easier to visualize how the success rate was compared to the failure rate each month. 

In the 'Outcomes Based on Goals' sheet, it would have been interesting to add another table where instead of narrowing down to the "plays" subcategory, to filter on parent category to 'theater' instead to understand how the two analysis stood next to each other. It would be insightful to see whether the success rate was more impacted by the goal or the launch date. It is impossible to compare when the parameters are different. Furthermore, adding a stacked bar graph with the y axis being the count of plays would have made it easier to visualize how the success rate was compared to the failure rate each goal range.