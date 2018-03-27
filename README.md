### Project Seadogs: NFL Player Arrests

## Questions

* What is the effect (if any) arrests have on a football players career or tenure with a team?
* Does arrest activity have any effect on a players perceived performance value?
* Does arrest activity have any effect on a players public brand?

## Summary of Findings

Overall, arrest activity appears to have a limited effect on an NFL players longevity with a team. Using data pulled from nflarrest.com, our team pulled 495 arrest records dating from January 2008 through March 2018. Over that timeframe, all 32 teams encountered arrest activity with the Houston Texans having the least and the Denver Broncos having the most (i.e., 9 and 29 instances, respectively). 
Our first theory assumed that type of charge would have the greatest effect on whether a player was traded/released. To test the theory, we totaled the type of charges based on arrest data and paired those charge types against when a player was traded/released*. Based on that analysis, our findings indicate that heavier charges, including assault/battery, domestic violence, and gun related charges led to much higher count of trades than lighter charges including, traffic offenses, theft, and disorderly conduct. However, the heavier types of charges are minimal in the aggregate view of arrest activity. 

Aside from type of charge, we hypothesized that arrest frequency would have a role in whether a player was traded/released. From that assumption, we limited our scope to the top 50 current players with the most arrests. Of those 50 players, 28 were neither traded or released with 270 days of any one of their arrests. Conversely, there were only a few instances where a trade/release occurred within two weeks of an arrest. In those circumstances, the type of crime played a larger role than frequency; there were only 7 instances where a DUI led to a trade. Based on these statistics, our conclusion is that arrest frequency has little effect on whether a player is traded/released.

*We considered a trade/release to be potentially correlated to an arrest if the trade/release occurred within 270 days of the arrest. This may feel longer than necessary, but in many instances, protracted team investigations extended the expected timeframe. Further, the longer period provides added confidence that we have accounted for all positive instances.

Generally speaking, it does appear that the public opinion of NFL players declines after a trade and/or committing a crime.  That said, to what extent the crime is responsible for a decline in overall sentiment is debatable. Other factors that could be more comprehensively measured alongside criminal activity might be player performance, team performance or some quasi-measurement of a player’s public persona as it relates to their off-the-field image (e.g. publically donates to charity, etc.). Of the sampled players, Kenny Britt, Marshawn Lynch, and Nigel Bradham seem to defy this trend the most. This divergence may simply be a result of a player’s relative “stickiness”, where the ability of the player to help a given team succeed simply outweighs the negative perception surrounding their criminal history.



#### Data Sources

Arrest Data(API):  nflarrest.com/api/
Trade Data (web scrape): prosportstransactions.com/football/
NFL Fantasy Data (web scrape): fantasydata.com
Twitter Sentiment (web scrape): https://developer.twitter.com/

#### Sentiment Analysis

Hutto, C.J. & Gilbert, E.E. (2014). VADER: A Parsimonious Rule-based Model for Sentiment Analysis of Social Media Text. Eighth International Conference on Weblogs and Social Media (ICWSM-14). Ann Arbor, MI, June 2014


![png](sd_datafetch.jpg)
