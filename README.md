# CSE-416A-network-analysis-Project
CSE 416A network analysis Project

Please find the detailed codes in: https://drive.google.com/open?id=1nh7jdL5PlmgkWGbmlouOT5Wz1eLQb2N_

## Abstract
Movie recommendation systems are becoming more important with increasing amount of user information and greater demands of user experience. One of the basic ideas of recommendation system is based on user similarity - to recommend the preferred items of similar users. In this work we aim to design and evaluate a new recommendation algorithm by modifying the traditional collaborative filtering recommendation algorithm with community detection of users from a similarity network. We also aim to try different methods of creating the similarity network by using various measures of user similarity. The database used for this project is the MovieLens database downloaded from its official website. We aim to predict the scores rated by users towards movies as the final output of our recommendation algorithm.

## Introduction
A recommendation system is one class of information filtering system that seeks to predict the "rating" or
"preference" a user would give to an item[2]. Recommendation systems are utilized in a variety of areas, and are
most commonly recognized as playlist generators for video and music services like Netflix, YouTube and Spotify.
One of the most traditional and wide-used technique used by recommendation systems is collaborative filtering, a
method of making predictions about the interests of a user by collecting preferences information from many other
users. The main goal of this project is to design and evaluate a new recommendation algorithm by modifying
the collaborative filtering with community detection of users from a created similarity network.
There are mainly six stages of this project: 1) First we will conduct an exploratory data analysis and
data wrangling to split the MovieLens database into training and testing sets. 2) Then we attempt to use the
database, which offers information of ratings given by users towards movies and characteristics of movies, to create
a baseline recommendation system using collaborative filtering technique. 3) For the next step, we will create a
weighted similarity-based network of users from the bipartite network of users and movies. 4) We then plan to
use one community detection algorithm for the weighted network to detect user communities and explore each
community’s preferred characteristics of movies as well as the similarities and differences among communities.
5) Based on the communities detected in the step four, we will modify the baseline recommendation system by
combing the detected communities into the algorithm. 6) With evaluating the new system as the last step, we
will discuss about the problems and possible further improvements of this project
