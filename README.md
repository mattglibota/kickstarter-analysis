# An Analysis of Kickstarter Campaigns
Performing analysis on Kickstarter data to uncover trends

![Goal](/Outcomes%20based%20on%20Goal%20update.PNG)
---
![LaunchDate](/Outcomes%20based%20on%20Launch%20Date.PNG)

### Executive Summary
There are a handful of strong observations from the Kickstarter analysis. Both the launch date and the goal amount can be used to estimate the overall success of a Kickstarter campaign. In future, I would suggest to set goal amount less than $20k and launch campaign in May to July.
____________________________________________

Below are a list of reasonable conclusions from the data:

1) As the goal amount increases from "less than $1000" bin to the "20k to $25k" bin, the percentage of successful campaigns decreases in a linear fashion from 76% to 45% success. In other words, as goal amounts increase the chance of success decreases. 

2) In over 1000 play campaigns, none were ever cancelled.

3) Due to small sample sizes (<=11, after goal amounts of $25k, there isn't enough data to conclusively determine if there is a strong correlation at these goal amounts. Suggestion is to set a goal amount below $25k.

3) The chance of a successful Theater campaign peaks in May and then continues to decline until December. The chance of success appears to exhibit strong seasonality behavior. It is over 50% more likely that a Theater campaign will be successful in May to Jul period, versus the remaining months.

There are a few limitations of the dataset:

1) It does not include distribution meeasures of backer donations. This exclusion could help determine if there was a large donation from a unique sponsor that skewed the campaign in reaching its goal.

2) It does not include Backer Levels (i.e. rewards for different donation levels). These rewards can influence a backers desire to contribute.

3) Does not include enough play-specific data to draw strong conclusions from higher goal amounts

Additional tables and graphs could help refine the estimation of success: 

1) Analyzing the average donation versus success will give insight into the distribution of backer donations and look at the impact of above limitation.

2) Creating a histogram of days open versus success could define a minimum amount of days needed for best chance at success

2) Looking at relationship of percent funded and goal amount could give us insight into external factor influence (e.g. marketing, familiarity with source material) on success. For example, take a data subset of Goal Amounts less than $1000, and look at distribution of Percent Funded.

Please note the outcomes based on goals analyzes the specific subset of Play-based campaigns, while the outcomes based on Launch Date analyzes the specific subset of Theater-based campaigns.

### Challenge
