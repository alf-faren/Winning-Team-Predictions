# Can we predict if Blue Team is winning?
#### Based on the popular game: League of Legends

![Popularity](/images/01.png)

Ever since the release of League of Legends back in October 27, 2009, the game has been on a rocket to the moon. Despite it being a game released just a little bit more than a decade ago, it is not showing any signs of decline as it releases major balance patches every year. Every year, they hold an event for all the regions - LPL(China), LCK(South Korea), LCS(North America), LEC(Europe), PCS(Southeast Asia), VCS(Vietnam), CBLOL(Brazil), TCL(Turkey), LJL(Japan), LLA(Latin America), OPL(Oceania), LCL(Commonweath of Independent States). 

Only the best of the best will be able to join such events. In order to find out who are among the top players, they play it out on a ranked ladder. The ranked ladder consists of Iron, Bronze, Silver, Gold, Platinum, Diamond, Masters, Grandmasters, and Challengers. You have to complete 10 placement matches that will determine where you currently stand on the ladder. 

![Diamond](/images/dia.png)

With this data set, we are going to determine the factors that will lead to the Blue Team winning the match within the Diamond ranks.

![Top features weight](/images/weight1.png)

A quick peek at the weighting of each feature, shows that the most influential factor would be the difference in gold between the red and blue teams. Gold is an important resource because you can acquire better items which in then leads to better stats for the champion that you are playing. 

![Features](/images/features.png)

Just like the weighting of the features, the bar graph above also demonstrates that the most important feature is the gold difference.

![PDP](/images/pdp.png)

By looking at this Partial Dependence Plot, it is skewed to the right. As long as the blue team is gaining more and more gold, they are gaining an advantage over the other team, but this can be also be said about the red team.

# Final Thoughts

A quick breakdown of these visualizations show that while it is possible to predict the outcome of the blue team winning, it is not always true. Within a single round, there can be unexpected factors that can turn it from a winning game to a losing one.
