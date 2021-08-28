# Expected Goals Model

## Introduction
Here, I will introduce the concept of expected goals (xG) and conduct an exploration of event data whille constructing a machine-learning model from this event data.

## Dataset
This dataset contains all the spatio-temporal events (passes, shots, fouls, etc.) that occur during all matches of an entire season.
A match event contains information about its position, time, outcome, player and characteristics.

Cick here to access [dataset](https://figshare.com/collections/Soccer_match_event_dataset/4415000/5)

## Topics covered
* Data Exploration
* Data Cleaning
* Exploratory Data Analysis
* Modeling Expected Goals
* The xG model
* Model Evaluation

## Conclusion
Logistic Regression performed with an accuracy of 89% for classifying every goal-scoring chance, and the likelihood of scoring.

Goals, as we know, are mostly random. We need to remember that every shot is unique, comprised of hundreds of different variables. We did not consider where the goalkeeper is positioned, if the shot was taken with a weak foot or strong foot, shot height at point of contact, the game state, home field advantage, if there are many bodies between the goal and the shot, etc.
