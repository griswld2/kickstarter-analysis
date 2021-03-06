# kickstarter-analysis

## Overview

The purpose of this analysis was to discover how successful different campaigns fared in relation to their launch dates and their funding goals.

## Analysis and Challenges

The analysis included creating two different charts. One based off data from a pivot table from the raw data and one based off of a secondary data frame that was created in a new worksheet in Excel [Kickstarter_Challenge.xlsx](https://github.com/griswld2/kickstarter-analysis/blob/main/Kickstarter_Challenge.xlsx).

![Theater_Outcomes_vs_Launch.png](https://github.com/griswld2/kickstarter-analysis/blob/main/Theater_Outcomes_vs_Launch.png)

The chart above shows the data that came from the pivot table. This requried creating a pivot table and also filtering data.

![Outcomes_vs_Goals.png](https://github.com/griswld2/kickstarter-analysis/blob/main/Outcomes_vs_Goals.png)

The Outcomes vs Goals chart required creating a new data frame and using the countifs function to bucket success, failed, and canceled plays by fundraising goals. It also required using the SUMS function in Excel and dividing the different fields by the total.

The challenge was to look at how theaters performed from a monthly perspective and how plays performed based off their campaign fundraising goals. 

Theater success peaked in the month of May and continued to see strong success throughout the summer months of June and July. 

Unsurprisingly, plays with lower campaign goals saw a higher level of success than plays with higher campaign goals. There are outliers within the data between $35,000 and $45,000 that saw a high success rate. However, these goal tiers also saw a low sample size (N < 20). Additional data would be required to determine if success at this fundraising goal tier isn't just due to a low sample size.

The biggest challenge was adding the date created conversion. Other possible challenges could be creating a pivot table and filtering data correctly or using the countifs formula.

## Results

Two interesting insights on the theater outcomes is that no cancellations occurred in the month of October, however, there was a spike in failed fundraising goals during this time period. Additionally, The holiday months of November and December saw poor results in reaching their fundraising goals. This could be due to patrons spending their money on holiday travels and presents.

One conclusion that can be drawn from the outcomes based on goals is that campaign fundraising goals that were less than $15,000 had a positive success rate. Setting smart and strategic goals that are obtainable creates an environment for success. 

Limitations of the data include that their was no way to determine how long of a campaign each media had. Additional charts that looked at correlations between success rates and category could be helpful to determine what the best media is to use to hit fundraising campaign goals. 
