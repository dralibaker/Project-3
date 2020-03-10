# Project-3

## Introduction
For this project, we analyzed the interactions that users have with articles on the IBM Watson Studio platform, and make recommendations to them about new articles you think they will like.
In order to determine which articles to show to each user, a study of the data available on the IBM Watson Studio platform was conducted. 

The project is divided into the following sections:

## I. Exploratory Data Analysis
Before making recommendations of any kind, we explored the data. 

## II. Rank Based Recommendations
To get started in building recommendations, we first found the most popular articles simply based on the most interactions. Since there are no ratings for any of the articles, it is easy to assume the articles with the most interactions are the most popular. These are then the articles we might recommend to new users (or anyone depending on what we know about them).

## III. User-User Based Collaborative Filtering
In order to build better recommendations for the users of IBM's platform, we could look at users that are similar in terms of the items they have interacted with. These items could then be recommended to the similar users. This would be a step in the right direction towards more personal recommendations for the users. You will implement this next.

## IV. Matrix Factorization
Finally, we completed an ML approach to building recommendations. Using the user-item interactions, we built out a matrix decomposition. Using decomposition, we got an idea of how well we can predict new articles an individual might interact with.

## V. Results & Discussion 
