# Machine-Learning-Project

TWIN: Personality-based Intelligent Recommender System
Poojith S Shetty, Prashant Reddy, Vinyas Kaushik Tumakunte Raghavendrarao {Shetty.poo, Reddy.pra, tumakunteraghaven.v}@husky.neu.edu INFO7390 ADS Fall 2017, Northeastern University
1. Abstract
To create the recommendation system the trip advisor data set, personality score data set, and reviews given by those users to different hotels data set, was taken into consideration. The data has been clustered based on the personality. After the clustering, the kmean cluster value was added as a column to the reviews dataset. Based on the username and Location input, the model looks at the users with similar personalities and outputs all the hotels which have rating 5.
To validate the given recommendation, the input of the username, and personality test inputs were given to to get the cluster. Then the prediction model is passed the kmean value and the hotel name, and using this the rating of the hotel is predicted. If the hotel is present in the training set then we have the predicted rating similar to the rating in the test dataset. The code was later deployed to google cloud using the flask application
