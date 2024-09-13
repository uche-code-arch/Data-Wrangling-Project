 I recently did a project with the muskets football team data where the task given was to:
 i) Create a full range cleaning of the data
 ii) Preprocess the cleaned data and transform it to a well-behaved data
 iii)Select input features for the outcome feature.
Also some sub-task were added to the main task, such as:
a)To extract the player name from the playerUrl column and create a new column known as the playerName.
 b)To create a new column from the Contract column and title it the player status with labels such as 'Active','Free','On-Loan'.
 c)Create 5 new categorical columns from the height,weight,Release-clause,value and wage columns and bucketize them into intervals of 10yrs,10kg,50k,50Mrespectively.
 d)Unpack the Positions column into as many columns as there are positions and assign a boolean value to it with the name of the column as playerPosition.
 e)Convert the wage,value and Release-clause columns to Float.
For this project i used the jupyterNotebook as my text editor,#Pandas for cleaning and preprocessing the data,hashtag#densityplot to check how normal the
distribution is in the data,#matplotlib.pyplot for visualization of the relationship between the input features and the outcome feature,Histogram to check for inbalance in the data
Seaborne for visualization of outliers. Interquartile range was used to check for skewness and outlier removal.
