# Predictive-modeling-with-tensorflow
includes linear,DNN and Hybrid models
This project reads movie data such as title, genre, top 3 actors'names and their facebook likes, director name and facebook likes, gross collections, number of voted users in imdb, number of critics in imdb etc
The aim of this project is to predict the imdb scores using the above data

The data for this project is sourced from https://github.com/sundeepblue/movie_rating_prediction and the final file movie_metadata.csv is used 

The following are the models build in tensor flow

Linear model : Predicts if movie rating is above 5 or not 

DNN classifier : Predicts if movie is poor <2.5, 2.5 < average <5, 5< good <7.5, 7.5<Excellent<10

Hybrid model A.K.A DNNLinearCombinedClassifier : Predicts if movie is poor <4, 4 < average <6, 6< good <8, 8<Excellent<10


The file Data Analysis helps in understanding the data and gathers insights on
Missing data
Anomolies
Correlation between the features 
correlation between the features and target
summary statistics
Data Distribution

This is where we analyse which features to be considered and which to be removed

After this file 
We can use any of the 3 model files to predict the target

Note:The performance of the three models cant be compared directly as the target is different for the three models

