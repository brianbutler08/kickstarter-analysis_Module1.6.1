# Module 1.6.1 Kickstater Analysis

## Background

For this project, we were approached by an up-and-coming playwright named Louise. She had written a new play titled *Fever* but needed to acquire the $10,000 of funding to get it produced. Louise had an interest in utilizing the online platform Kickstarter as a method to crowdfund her project and wanted to work with a data analyst proficient in Excel to explore some of the available Kickstarter data in order to maximize success. The general idea was that if we could identify some characteristics of successfully funded campaigns, we could perhaps apply that knowledge to Louise’s Kickstarter launch.!

We acquired a dataset (n=4,114) of various Kickstarter campaigns from 2009 to 2017, which included the following fields:
- Project name
- Project blurb
- Funding goal
- Amount pledged
- Outcome of campaign
- Country of origin
- Currency
- Date that the campaign opened
- Date that the campaign closed
- Number of backers
- If the campaign was a staff pick or highlighted
- Campaign category and subcategory

# Primary Findings

## Campaign Success Overview

Of the nine general categories of fundraising campaigns, the theater category had the most number of projects during this time period (1393), almost twice the number of the next most popular project (music – 700). When looking at only the US based projects, this trend continued, with 912 campaigns categorized as “theater”. Additionally, theater projects were the most successful during this time period, with 525 projects being successfully funded. And of those projects that were successful, 412 of them were plays, making “plays” the subcategory with the most successfully funded campaigns in the US.

![Parent Category Outcomes Bar chart](https://github.com/brianbutler08/kickstarter-analysis_Module1.6.1/blob/main/Parent%20Category%20Outcomes.png?raw=true)

## Timing Your Campaign Launch

When we looked at the timing of when campaigns were launched, it appears that there is a correlation between launch month and outcome. Overall, May was the most successful launch month for campaigns, with success rates gradually tapering downward over the summer.

![Line graph of campaign launch months](https://github.com/brianbutler08/kickstarter-analysis_Module1.6.1/blob/main/Outcomes%20Based%20on%20Launch%20Date.png?raw=true)

Specifically, theater projects followed this same pattern. Failure rates stayed relatively consistent over this same time period.


![Theater Outcomes Based on Launch Month](https://github.com/brianbutler08/kickstarter-analysis_Module1.6.1/blob/main/Theater%20Outcomes%20Based%20on%20Launch%20Date.png?raw=true)

## Analysis of *Foresight*

Because Louise had an interest in the British play *Foresight*, we looked at it specifically to see how successful its campaign was. It was fully funded, despite only having seventeen backers, leading to a high average donation of $117.88 per person. Additionally, the campaign ran for just under a month, less than the dataset average of 33 days. 

## Edinburgh Festival 
 
Louise was inspired by five specific plays that she saw at the Edinburgh Festival Fringe, so we looked in detail to see if they could provide any insights into creating a successful crowdfunding campaign. All five plays were successful in meeting their funding goal. They each had a relatively modest goal, with the highest goal being just $4000 and the average being $2100. They each had a good number of backers (mean = 62.4), with each person contributing an average of $40.5.

## Failure vs Success
 
In order to explore the possible differences in US campaigns that were successful versus those that failed, we looked at some basic descriptive statistics by campaign outcome. The mean goal for successful projects ($5049) was less than half of the failed projects ($10554). Additionally, the mean amount pledged to successful campaigns ($5602) was ten times more than the mean for those campaigns that failed to meet their funding goals ($559). On the surface, it appears that the failed projects were generally setting their goals unrealistically high and they were unable to generate enough support to even come close to those meeting those goals. 
 
By graphing campaign outcomes as box plots, it becomes obvious that Louise may want to consider lowering her funding expectations if she plans to target the British market. The average Kickstarter goal for plays in GB is around $4000, which is Louise’s current goal. However, among successful campaigns, the median amount pledged was only $1877. Therefore, only half of the projects raised less than half of what Louise would require. If she is unable to lower her projected costs, it may be important to look at other possible locations fo the campaign.
