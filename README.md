# La-liga
Predict la liga matches for 2023 season.


-Scrap Web for data
-Use several models to predict winners


### Predictors for model
Venue- home and away advantage is signiificant in football. so i am going to convert home and away into numbers

Team- give each team a code

Time- do some teams play better at certain times of the day? Night games and mid afternoon games can have different outcomes because of several factors like heat, rain, visibility, crowd energy amanog many others

Day- same as above. Sunday games have more viewers as opposed to midweek. Could such pressure affect performance



### Using Random forest model. 
Random forest helps pick up non linear trends in data. there i s no clear relantionship between hour and winning. this model will help us determine such trends.

Trained on data from previous seasons.
Tetsed on current season.

precision= 0.549

#### Improving predictors 
Form- current form is important in determining the outcome of next game. so we can leverage this further imporve our model. in this case past 4 games are being used to detemine form

Goals For, Goals Against,Pentaly kick attempts, Distance a shot is taken from, Free kicks, Shots on target,Penalty kicks, Shots, 


#### Variable importance plot 
Done a variable importance plot to determine what factors the random forest model thought were important

### Lets try a Descion Tree Regressor
A decision tree might split the data based on the home team's win/loss record, the away team's win/loss record, etc. Each of these splits creates a subset of the data that is more homogeneous in terms of the outcome (win or loss), allowing the tree to make more accurate predictions based on the remaining features

precision = 0.552

### Neural Network 
Neural networks are a class of algorithms that are inspired by the structure and function of the human brain. They can be used for a wide range of tasks, including classification, and have been shown to be effective at predicting winners and losers in various domains. 


precision = 0.551

The best model only works 55% of the time.
