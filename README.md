# La-liga
Predict la liga matches for 2023 season.


-Scrap Web for data
-Use several models to predict winners


# Predictors for model
Venue- home and away advantage is signiificant in football. so i am going to convert home and away into numbers

Team- give each team a code

Time- do some teams play better at certain times of the day? Night games and mid afternoon games can have different outcomes because of several factors like heat, rain, visibility, crowd energy amanog many others

Day- same as above. Sunday games have more viewers as opposed to midweek. Could such pressure affect performance



# Using Random forest model. 
Random forest helps pick up non linear trends in data. there i s no clear relantionship between hour and winning. this model will help us determine such trends.

Trained on data from previous seasons.
Tetsed on current season.

precision 1= 0.564

# Improving predictors 
Form- current form is important in determining the outcome of next game. so we can leverage this further imporve our model. in this case past 4 games are being used to detemine form

Goals For, Goals Against,Pentaly kick attempts, Distance a shot is taken from, Free kicks, Shots on target,Penalty kicks, Shots, 





