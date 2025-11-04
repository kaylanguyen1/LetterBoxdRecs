#Movie Recommendation System through LetterBoxd



##Overview:

This project is a movie recommendation program that generates personalized movie suggestions based on your Letterboxd profile and the profile of 3 of your friends/other LetterBoxd users.



This program uses collaborative filtering to find movies to suggest the movies you would be most likely to enjoy.



This program was implemeneted using:

- Apache Spark and Spark DataFrames
- Web scraping with BeautifulSoup
- Python and ran on Google Colab


Features:

- Scrapes films watched and their rating from LetterBoxd  profiles
- Builds a recommendation model using Alternating Least Squares (ALS)
- Provides a ranked list of recommended movies with their predicted rating for the user

Collaborative Filtering:

- a technique used in building personalized recommendation systems (also used by companies like Amazon, Netflix, and Spotify) to predict user interests by grouping users with similar past preferences



Alternating Least Squares:

- an algorithm used for matrix factorization that works by iteratively optimizing 2 matrices user factors and item factors alternating between the two to predict missing ratings to suggest movies a user hasn't rated yet



How To Run:

1. Download code or clone git url
2. Open code in Google Colab
3. Run cell 1 once only to install dependencies, then run cell 2 as many times as you want by inputting different Letterboxd usernames

