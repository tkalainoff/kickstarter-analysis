# Kickstarting with Excel

## Overview of Project

We have been working with an up and coming playwright, Louise, who is interested in starting a fundraising campaign for her play Fever. She has estimated the budget for Fever to be around $10,000. Through our analysis, we will help determine if there are any specific elements of fundraising campaign that lead to a successful outcomes, with the ultimate goal of helping our playwright Louise plan hers.

### Purpose

The purpose of this analysis is to have a deeper understanding of the outcomes of various plays based on their launch dates and fundraising goals to help Louise decide when to launch her own campaign and what her fundraising goal should be in order to be the most successful.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

For theater outcomes based on launch date, we can see in the line chart that both lines for successful and failed campaigns follow a similar trend - increasing from March to May and steadily decreasing from May to December with a slight uptick in October. 

https://github.com/tkalainoff/kickstarter-analysis/blob/main/Theater_Outcomes_vs_Launch.png

### Analysis of Outcomes Based on Goals

For outcomes based on goals of theater campaigns, we can see that no plays were canceled in our crowdfunding data and that the trends for successful and failed campaigns mirror each other in the chart, with three points where they cross each other. Successful campaigns account for the majority of campaigns with goals from 'Less Than 1000' to '1000 to 14999' to '35000 to 39999' to '40000 to 44999' and failed campaigns account for the majority of campaigns with goals of '2000 to 24999' to '30000 to 34999' and '45000 to 49999' to 'Greater Than 50000'. 

### Challenges and Difficulties Encountered

I was challenged when populating the Outcome Based on Goals sheet - I made numerous attempts to make sure all criteria was counted in the COUNTIFS function and then had to ensure that the criteria ranges were not moving when copied over the rest of the columns with '$'s. I was also a little surprised by the 'Canceled' category in both graphs and had to investigate the differences in the filtering of each graph to understand why the values in that category were presenting differently.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

That Spring/Q2 would be the best time to launch a fundraising campaign with 111 successful campaigns in the month of May. Summer/Q3 would also be a good time to launch a campaign though the successful campaigns steadily decline during this quarter. Finally, the month of October should be considered for launch dates as it presents an uptick within a steadily declining quarter and has 0 canceled campaigns. 

- What can you conclude about the Outcomes based on Goals?

That Louise's anticipated budget of $10,000 would fall into the goal range where the majority of campaigns were successful (54%). That campaign goal ranges of Less Than $1000 - $14999 or $35000 - $44999 are also likely to be successful. It may make sense for Louise to pick a campaign goal between Less than $1000 and $4999 - goals in this range had more than 70% of campaigns turn out successful. 

- What are some limitations of this dataset?

This dataset seems pretty comprehensive. We are unable to see more granular data like each individual donation for a specific campaign, but the 'average donation' and 'backers count' still provides a comprehensive picture of that data. One area we are limited in is data for why a campaign got canceled - did it simply not raise enough money by the deadline? Was it canceled in the middle of the campaign for other reasons? etc. 

- What are some other possible tables and/or graphs that we could create?

We could show similar graphs that show the same information but looking specifically at plays only in the US, as Louise's play Fever will be happening in the United States. We could also take a deeper look into each campaign and have a column graph with a line overlaid to see the relationship between number of backers (represented by the columns) vs campaign goal (represented by the line). It would also be good to visualize the duration of campaigns and see if there is any relationship to a campaigns success.
