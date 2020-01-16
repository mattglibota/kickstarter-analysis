# An Analysis of Kickstarter Campaigns
Performing analysis on Kickstarter data to uncover trends

![Goals](/Outcomes%20based%20on%20Goal.PNG)
---
![LaunchDate](/Outcomes%20based%20on%20Launch%20Date.PNG)

There are a handful of strong observations from the Kickstarter analysis. Both the launch date and the goal amount can be used to estimate the overall success of a Kickstarter campaign.

Below are a list of reasonable conclusions from the data:

1) As the goal amount increases from "less than $1000" bin to the "$15k to $20k" bin, the percentage of successful campaigns decreases in a relatively linearly by around 25% points. In other words, if goal amounts are less than $20k, the lower the goal amount the higher the chance of success.

2) The percentage of successful campaigns remains relatively flat between 40 - 50% from "$15k to 20k" bin to the "$40k to 45k" bin. In other words, if goals amounts are between $15k to $45k, the chance of success remains relatively the same.

3) The chance of a successful Theater campaign peaks in May and then continues to decline until December. The chance of success appears to exhibit strong seasonality behavior. It is over 50% more likely that a Theater campaign will be successful in May to Jul period, versus the remaining months.

There are a few limitations of the dataset:

1) It does not include distribution meeasures of backer donations. This exclusion could help determine if there was a large donation from a unique sponsor that skewed the campaign in reaching its goal.

2) It does not include Backer Levels (i.e. rewards for different donation levels). These rewards can influence a backers desire to contribute.

Additional tables and graphs could help refine the estimation of success: 

1) Analyzing the average donation versus success will give insight into the distribution of backer donations and look at the impact of above limitation.

2) Creating a histogram of days open versus success could define a minimum amount of days needed for best chance at success

2) Looking at relationship of percent funded and goal amount could give us insight into external factor influence (e.g. marketing, familiarity with source material) on success. For example, take a data subset of Goal Amounts less than $1000, and look at distribution of Percent Funded.

Please note the outcomes based on goals analyzes the entire dataset for trends, while the outcomes based on Launch Date analyzes the specific subset of Theater-based campaigns.

### Challenge
