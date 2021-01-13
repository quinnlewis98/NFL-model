# NFL-model

Quinn Lewis
qpl9ef@virginia.edu

This project uses linear regression and machine learning to calculate the spreads and totals for NFL games. 

Six numbers are taken from every matchup and put into a matrix of size (len(games),6) A result matrix keeps track of the scores of those matchups. The six stats are:
-Home Offense
-Away Offense
-Penalty Differential
-Turnover Differential
-Scoring Percentage Differential
-Homefield (constant)

Using Least Squares Linear Regression, the ideal weights for these six stats were calculated. These were then used to calculate future matchups. 

Starting at week 10, when this model was created, this model predicted 67% of games correctly against the spread. 

For next season, I would be interested in saving each teams stats every week rather than using updated stats for past weeks. 

Game logs from http://www.habitatring.com/
Team stats from https://www.pro-football-reference.com/
