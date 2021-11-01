# Module-1-Challenge

# Kickstarting with Excel

## Overview of Project

### Purpose

- Determine the correlation of Kickstarter fundraising outcomes with the launch date

- Determine the correlation of Kickstarter fundraising outcomes with the goal amount

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
- Process and clean data set to provide Launch month and Launch year
- Filter dataset to appropriate population (parent category = theater)
- Visualize the results based on the counts of successful, failed and canceled outcomes over each month

### Analysis of Outcomes Based on Goals
- Filter dataset to appropriate population (subcategory = plays)
- Create bins for each goal amount and outcome
- Calculate the percentage of successful, failed and canceled outcomes
- Visualize the results based on the percentage of outcomes and binned goal amounts

### Challenges and Difficulties Encountered
- Raw data for date values not in a format that Excel can understand for charting
- Must use conditional counts to calculate the outcomes for each binned goal amount

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
	- Successful outcomes show a seasonal trend for the sampled dataset. The greatest number of successful outcomes occur around the middle of the year (May / June) and the least number of successful outcomes occur toward the end / beginning of the year (December / January).
	- Launch Date does play a role in the outcome of a Kickstarter campaign, and thus should be planned accordingly to increase the probability of success. 


- What can you conclude about the Outcomes based on Goals?
	- Smaller fundraising goals have a higher chance of success than larger goals. Fundraising in smaller chunks may help reach the desired goal. 

- What are some limitations of this dataset?
	- The dataset is very spotty above the $25K fundraising mark for plays. Thus conclusions above this amount have lower confidence.
	- Genre and rating of play not known. 
	- No demographic or target audience information is included.
	- Impacts of advertising and marketing KPI's are not included (such as page views / links clicked / time spent on website / etc.)


- What are some other possible tables and/or graphs that we could create?
	- Further analysis and visualizations can be presented based on the duration of the campaign to see if the campaign spread has an impact on the outcome success rate.
	- Heatmap visualization based on Country and Average Donation
