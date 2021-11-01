# About
Using a dataset obtained from [Kaggle](https://www.kaggle.com), this project attempts to identify different generes of videos by analyzing trending U.S. Youtube video's tags, descriptions, and titles.
Data is trimmed and the more common and unnecessary words are weeded out, which are then thrown into a bag of words for vectorization.
Words that were weeded out including common english words like "to" and "a" as well as words like "youtube.com", "instagram", and "patreon" that provided no meaningful information to the categorical genres.

This project utilized a Fully Connected Neural Network and a Convultion Neural Network to compare two different models on a dataset as well as Linear Regression for evaluation. 

# Viewing the project 
This project was done in Python notebook and can be viewed alternatively in Jupyter's nbviewer for the best results. 
[Link to the project's nbviewer](https://nbviewer.org/github/KyleNThao/Youtube_BiClassification/blob/main/YouTube_Trending_Binary_Classification.ipynb)

# Dataset
While this project only utilized the U.S. dataset of trending videos, the full set gathered by the user Mitchell J., can be found online and downloaded here:
[Trending Youtube Video Statistics](https://www.kaggle.com/datasnaek/youtube-new)
