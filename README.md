# nba-rookie-data-analysis

**Note: this was the final project for CS115 at the University of Wisconsin-La Crosse*

Used a dataset from Kaggle that included the statistics from each NBA (National Basketball Association) player's rookie year (first year in the league) from ~1985 to 2016 in order to not only compare different statistics and trends, but to also determine which NBA player had the best rookie season. 

When comparing trends across different variables, I put various variables in both the x and y-axes across multiple different scatterplots. I also included a line-of-best-fit for each graph in order to see the overall trend.

When determining who had the best rookie season, I looked at two statistics: Offensive Rating and Defensive Rating. These both already have official ways of calculation, however, due to limitations regarding software (particularly, when dividing by zero (one part of offensive rating is calculating the percentage of three-pointers made, however, there is a sizeable chunk of players who have never shot a three-pointer, therefore, the calculation would be 0/0, which is undefined and crashes the program)), I had to make my own formulas for calculating each rating. From the calculations of those ratings, I created one more statistic: "Overall Rating," which was a combination of the Offensive and Defensive Ratings from each player (although, Defensive Ratings were weighted slightly higher since my formulas resulted in low Defensive Ratings in comparison to Offensive Ratings). This statistic of Overall Rating was used to determine who had the best rookie year.

My findings were very similar to the general consensus among NBA fans on who had the best rookie year. The players who had the highest Overall Rating in this project were players like Allen Iverson, Michael Jordan, and Larry Bird, all players who are consistently in the talk for players with the best rookie season.

In addition to the visual graphs for comparing trends across different statistics, I also included bar graphs for these ratings by the top 10 players in each category/statistic.
