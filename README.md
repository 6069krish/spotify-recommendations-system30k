Spotify Song Recommendation System

This project was developed as part of the Nights and Weekends Season 5, Week 2 task. The objective was to re-iterate or basically re-launch my actual product—a Spotify song recommendation system.

Overview

The Spotify Song Recommendation System is designed to provide users with a list of recommended songs based on a login interface. The system leverages the Spotify API to fetch song features and uses a custom-trained model to identify and recommend similar songs.

Features

Using your spotify credentials: i have made this version where you have to upload your spotify credentials through which you have to select a playlist of yours so that it can recommend songs based on your music taste. Datasets used: for this project i have only used a 50 songs playlist created by spotify as my dataset but you can totally use a much larger dataset i.e some of them are "Million Playlist Dataset MPD" or "yama erenay's kaggle dataset"

Song Recommendation: Based on the input song's features, the system generates a list of 40 recommended songs, for this launch i have used a more bigger, 30k songs dataset from a dataset i found in kaggle

Project Structure The project consists of the following key components:

Data Preparation: Processing and preparing song data for training. Model Training: Training a recommendation model using the song features. Recommendation System: Implementing the function to recommend songs based on a given song URL. Jupyter Notebooks: Includes code and explanations for each step.
