# Regression-Analysis-of-400-movies
You are given the dataset “movieReplicationSet.csv” which features ratings data of 400 movies from 1097 research participants. 
Impute the missing ratings with a blend (50:50) of the arithmetic mean of each column and each row. (Let’s say that the rating of user 350 for movie 200 is missing and that the average rating of this user for other movies is 4 and the average rating (by other users) for this movie is 3, then the to-be-imputed rating would be 3.5, using this method.)
For each of the 400 movies, use a simple linear regression model to predict the ratings. Use the ratings of the *other* 399 movies in the dataset to predict the ratings of each movie (that means you’ll have to build 399 models for each of the 400 movies).
For each of the 400 movies, find the movie that predicts ratings the best. 
Then report the average COD (Coefficient of determination) of those 400 simple linear regression models. 
Please include a histogram of these 400 COD (Coefficient of determination) values 
and a table with the 10 movies that are most easily predicted from the ratings of a single other movie 
and the 10 movies that are hardest to predict from the ratings of a single other movie (and their associated COD (Coefficient of determination) values, 
as well as which movie ratings are the best predictor, so this table should have 3 columns).
