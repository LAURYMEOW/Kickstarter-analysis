# Kickstarting with Excel

## Overview of Project

At Louise's request, we had been working on a fundraising strategy for the kickstarting of her play entitled FEVER based on past experiences of other plays in the same category. 
According to a previous report, the results were sent to us and we know that it was close to its goal. So it could be considered that the strategy was good but could improve. 
Then, Louise considers that an important factor was missing and suggest us to analyze the behavior of the campaigns of the other plays in order to find the areas of opportunity and improve her strategy for her next play to present.

### Purpose
With the above information we are going to do an analysis focused on the behavior of the determining factors in fundraising campaigns.
It is clear that a deeper analysis of the campaigns is required, so we have decided to break them down into two types, one by their launch date and the other by the goals.

For both we use the KICKSTARTED database and Excel software.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
From the available information we create a pivot table where we relate the results of the campaigns with their launch date. 
As it is an analysis by launch date, we have decided to break down the information by months, so we have a more detailed and timely view of its behavior. 
It is important to verify that the variables that we are reviewing are the appropriate ones according to the relationship that we are analyzing and that they are properly filtered in the pivot table. 
In our case we are interested in knowing the outcomes of the fundraising campaigns by launch date for plays. For that we choose to put the months in the rows and the results in the columns, filtering by years and by category.
In this way we obtain a tablet like the following:

With the above information we obtain a pivot chart that allows us to better visualize the behavior of the data. 
We had use the linear pivot chart because we are considering a behavior over time.

![Theater Outcomes by Lauch Date](path/to/Theater Outcomes by Lauch Date.png)

In the chart with the same name as this first analysis can be seen that the month in which the campaigns have been most successful was May. 
While December seems to be the month with the worst success performance. 
Failed campaigns show that May and October are also not good launch months.

### Analysis of Outcomes Based on Goals

For this analysis, an main column was created with intervals of amounts of funds in order to break down the information and have a more detailed visualization of it. 
Twelve intervals were created. That started at less than 1,000 dollars and increased from 5,000 to 5,000 until reaching 50,000 or more; and they were related to the number of cases of successful, failures and cancellations to assess their impact. 
Later, percentages were taken to make the results more understandable and they were graphed.

![Outcomes_vs_Goals](https://github.com/LAURYMEOW/Kickstarter-analysis/blob/main/Outcomes_vs_Goals.png)

On the chart with the same name as this analysis, can be seen that the success campaigns are those that had a reduced fund goals of between $1,000 and $15,000 dollars, while those that had the greatest number of failures were those that expected larger amounts of funds, specifically $45,000 or more. 
In addition, a campaign with a raising funds expectations around $30,000 is insecure.


### Challenges and Difficulties Encountered

The challenge in the first exercise can be to identify the variables and their relationships that we are interested in analyzing in order to know what is their place in the pivot table and achieve a sensible analysis.

The challenge in the second analysis was to populated the columns of the number of cases of each outcomes with the COUNTIFS formula because I had to do it manually. I couldn't find a way to automate it.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

I can conclude that analyzing the campaigns by release date of different works of the same Fever category is useful to develop the strategy for a new project in the same field because it gives us certain reliability for the proposal and decision making.

In the case that concerns us, the evidence indicates that a work like that of Fever requires planning a fundraising campaign for the month of May to guarantee a greater approach to the target funds.


- What can you conclude about the Outcomes based on Goals?

As in the previous case, an analysis of the campaigns by funds goals is also very useful because it allows us to see up to what range of collection it is pertinent to establish to the backers so that they are encouraged to support the play without feeling at risk.
In the case of the FEVER play, we can see in the analysis that the theater plays related to the one of our interest were more successful, establishing an austere but sufficient fund objective according to the expected expenses. Louis had considered a collection of approximately $10,000, which is among the success percentages of 54%, which although it is greater than 50%, is not as reliable because the percentage of failed cases is also high at 44%. Due to the above, it is recommended to make a new quote to reduce the fund objective and thus guarantee a greater approach to the established objective.


- What are some limitations of this dataset?

Updating the data would be of great help to know what the behavior of the campaigns has been during and with the new normality caused by the pandemic and to adapt the strategies to this new context.

- What are some other possible tables and/or graphs that we could create?

Probably an analysis on the backers and the fundraising goals could give us interesting information that could complement the previous two.



