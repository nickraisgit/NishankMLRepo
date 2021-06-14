Author: ***Nishank Raisinghani***

Project: ***Predicting the NBA Finals Champion using a regression tree algorithm***

This is a project to predict the final rankings of the NBA using regular season data. I trained a decision tree regression model to learn data from the past 5 years, since the 2014-2015 season.
The reason I didn't go back further is because that season was the year that most teams starting taking 30 threes a game, and if I went back further the model would have favored teams with a better mid range game and good defense, like the Spurs.
What I realized while creating this model was that a huge factor was age, and that more experienced veteran teams do much better in the playoffs than younger teans, which is why my model predicted either the Jazz or the Suns winning the finals.
Also, this model does not account for injuries during the regular season which is why teams like the Nets aren't a clear frontrunner. Basketball is also not played in a vacuum, therefore the model does not account for "playoff performers".
Using this model and noticing the trends we can come up with a recipe for a championship winning team. There are a few main factors, being elite on both sides of the ball, not just one, limiting turnovers, shooting a lot of threes at a high percentage, and ***veteran leadership/experience***.
This data came from basketball reference and the model was created using scikit learn.
