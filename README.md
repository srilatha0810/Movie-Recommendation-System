## Abstract
Recommendation systems have developed over the years, making search and find much
easier. Movie recommendation systems, in particular, help movie enthusiasts by suggesting
different movies, based on the user’s interest. This saves the user from the long process of
choosing from a large set of movies, which can go up to thousands and millions. The intent
of this project is to focus on the interpretation of the two different approaches of the movie
recommendation system, namely Collaborative filtering and Content-based filtering. This
will be done by implementing both filtering systems by use of the required algorithms and
prediction metrics, along with an appropriate dataset. The end-result is a list of movie
recommendations and a detailed analysis of each system, leading to the conclusion that
Collaborative filtering is the better approach. 

## Problem Statement
When having various approaches for implementing a movie recommendation system, there
is always one approach better than the other in terms of producing efficient
recommendations to the user.
While content-based filtering is used when developing a movie recommendation system
because of its simplicity, it has many drawbacks.
We have to depend upon the user for recommending any movie, we need an extensive set
of data.
Another major problem is that we need to start from scratch, because a new user will not
have already reviewed any movie yet. Hence, the user will not have the best experience.
Last but not least, with content-based filtering we won’t get a variety of movie
recommendations but only movies within the user’s preference zone.

## Solution
This is where Collaborative filtering comes into the picture. Based on similar interests, we
will be able to form clusters of users.
A CF Recommendation System is advantageous because it does not face the item cold-start
problem, which is faced in content-based RS. Even when no information from a user is
available regarding a particular genre, we can still predict the movie rating.
It is more flexible as well. Over time, it can capture any changes in interest the user may
have.
Hence, Collaborative Filtering is a more efficient approach to generate movie
recommendations within and outside the user’s preference zone which results in a variety
of recommendations.

## Proposed System
Movie Recommendations over the years have been developed using appropriate filtering
systems. When it comes to these filtering techniques, the two most commonly used systems
are content-based filtering system and collaborative filtering system.
One is content-based filtering, where we try to profile the user’s interests using
information collected, and recommend items based on that profile. The second one is
collaborative filtering, where we try to group similar users together and use information
about the group to make recommendations to the user.
The intent of this project is to use both the filtering approaches in implementing a movie
recommendation system with the necessary algorithms and metrics, give a detailed
analysis of each system, compare and show how collaborative filtering system is a more
efficient approach when generating movie recommendations. Each filtering system has
its own algorithms and metrics to be used. We will be using KNN, TF-IDF, Cosine
similarity and a range of technologies
