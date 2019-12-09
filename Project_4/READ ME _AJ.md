# Project 4 - Spotify Playlist Predictor


## Executive Summary

We will evaluate two data from songs played on spotify and user interactions to develop a model to accurately classify a new song to a playlist.

We will use several song features along with sentifment for the construction of this model. 

The playlist we will classify include 'XXXX'. We suspect these playlist to have some overlap with features, but a song will only be classified to a single playlist.



## The Modeling Process

 We will use a mixture of techniqeus including Logistical Regression, K Nearest Neighbors, and Natural Language Processing. We will pipeline these methods together and also use grid search techniques to determine the best construction of this model.

Success would be to create a model that predicts the proper playlist of a given title. An r2 score of more than 65% woudl be an effective working model.


## Data Sourcing and Preperation

For this evaluation we pulled in 500,000 song plays with corresponding user interactions provided by Spotify and originally sourced by 

Asmita Poddar, Eva Zangerle, and Yi-Hsuan Yang
for: A New Benchmark Dataset for Building Context-Aware Music Recommender Systems
http://mac.citi.sinica.edu.tw/~yang/pub/poddar18smc.pdf
date = 2018-07-04
discovered via https://zenodo.org/record/3247476#.Xa3T-JNKgWo


#### Attributes from Spotify.
- song title
- aritst
- song sound features
- user features


## Jupyter Notebook Structure

Jupyter Notebook walks through our modeling process with additional information into each model including:

- Creation Techniques
- features included
- validation methods
- model score
- conclusion of model results.

## Deliverables

The project file includes each work element or tool used during this initial evaluation including: -  
- Jupytern Code Notebook (Models)
- Readme file with executive summary
- Data Files for each list
- Combined data files
- Conclusions Reccomendations
