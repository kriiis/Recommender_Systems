# WBSFlix - Recommender System for Movies

This Repo contains:

data folder - all the data files as csv
resources folder - resource file from our WBS Trainer

wbsflix.ipynb - my jupyter notebook with 3 different recommender chat-bots

## Popularity based recommender

The popularity based recommender suggest movies based on total popularity scores for movies with a certain amount of total ratings.
If the recommended movies are not valueable for the user, it is possible to get more precise recommendations by enterin a year.

## Item based recommender

The Item based recommender suggests a movie based on a movie that the user enters. Therefore the movie database is searched for movies that contain the input string. If there is more then 1 matching film in the database the user can select the film he wants from a list. At the end the chat-bot recommends a similar movie to the user.

## User based recommender

The user based recommender suggests a movie for a certain user (how enters his/her user id) based on cosine similarity to the other users in the database.

