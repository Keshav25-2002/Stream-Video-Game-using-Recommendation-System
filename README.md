# Stream-Video-Game-using-Recommendation-System

This project aims to build a recommendation system for stream video games. The recommendation system is based on collaborative filtering, which is a technique commonly 

used in the industry to recommend products to users based on their past interactions with similar users.

Data

The data used for this project is a public dataset from Kaggle containing information about stream video games, such as the name of the game, the number of viewers, and 

the number of followers. The dataset is in a CSV format and contains information about more than 1,000 video games.

Model

The recommendation system is based on collaborative filtering, which is implemented using the Surprise library in Python. The Surprise library is a powerful library 

for building and evaluating recommendation systems. The model is trained on the dataset using the K-Nearest Neighbors algorithm with cosine similarity as the 

similarity measure.

Usage

To use the recommendation system, simply run the recommendation_system.py file. The script will prompt you to enter the name of the video game you want to get 

recommendations for. Once you enter the name, the script will return a list of recommended video games based on the collaborative filtering model.

Skills and Technologies Used

Python

Pandas

NumPy

Scikit-learn

Surprise

Collaborative filtering

K-Nearest Neighbors algorithm

Cosine similarity

Future Improvements:

Incorporating content-based filtering to improve the recommendations.

Building a web application for users to interact with the recommendation system.

Incorporating real-time data to make more personalized recommenda
