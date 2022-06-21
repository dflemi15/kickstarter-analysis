# kickstarter-analysis
Performing analysis on Kickstarter data to uncover trends
# Kickstarting with Excel

## Overview of Project

We are helping Louise with the analysis of the how her campaigns fared based on launch date data provided. 

### Purpose

By doing this, we will be able to determine what events were successful and which ones were not. We can also do a micro analysis on the factors that may have played in a role in an events success or failure.

## Analysis and Challenges

My analysis consisted of a two phased approach to understanding the outcomes of each event. First, I looked at the outcomes based on launch date and then continued to look at outcomes based on the set financial goal.

### Analysis of Outcomes Based on Launch Date

In order to provide the analysis of outcomes based on date, I used the “Years ()” function to generate a column in the dataset that provided the year each event took place. 

 

Once complete, a pivot table was developed that divided the data into several categories (successful, failed, and cancelled) which could be filtered by type of event and year. 

 

Once the pivot table was created, I was able to use new dataset to create a line graph (please see submitted images).

### Analysis of Outcomes Based on Goals

To begin the analysis based on goals, I started by using a “COUNTIFS ()” function in order to partition the outcomes data into categories based on various ranges of goal amounts. This data was also filtered specifically for plays. An example of the method is illustrated as follows:

 

As you can also see above, the percentage of each outcome was calculated by dividing the value of each outcome by the total number of each outcome. This information was then used to generate another line graph (please see uploaded image).
 

### Challenges and Difficulties Encountered

One of the challenges I encountered was with coding the formula in the “
Outcome Based on Goals” deliverable. I had some trouble getting the COUNTIFS () function to work. I realized that I did not lock my cells for each column I used in the Kickstarter dataset tab. Once the cells were locked, I was able to continue my analysis. This tends to be a common issue when dealing with complex functions with several layers of criteria.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

It appears we can conclude that the most successful events were launched in the summertime between May and July based on the data for theater events. In addition, we can also conclude that towards the end of the year, starting around October, success appears to decline, and the rate of failed events increase to close the same level of successful events.

- What can you conclude about the Outcomes based on Goals?

One conclusion we can make is that goals set to a value of $4999 or less, have a higher percentage of success than any other value range (73-76%). As the values increase, generally, the failure rates increase as well. The data does show some success in the higher value ranges, but there does not appear to be enough data to be able to contradict the conclusion that failure rates increase with increase in goal size.

- What are some limitations of this dataset?

The dataset does not have enough data points for events within the higher goal value ranges ($25k and up) to really determine if there is an inverse relationship between higher goal values and success rates. 


- What are some other possible tables and/or graphs that we could create?

A pie chart could be used to represent the success/failure percentages for the outcome-based goals analysis. Each range would need to be given its own pie chart which may not be the best use of time. For the launch date analysis, a clustered column chart could be used to demonstrate the success/failure/cancelled for each month.
