# Movie-Recommendation-System

-Problem Statement
With so many movies available today, it becomes difficult for users to decide what to watch. The goal of this project is to build a simple movie recommendation system that suggests movies similar to a given movie based on its content.

-Dataset
The dataset used in this project is the TMDB 5000 Movies Dataset from Kaggle.
It contains information such as:


Movie title


Genres


Overview (short description of the movie)


For simplicity, only the relevant columns (title, genres, overview) were used.

-Approach
This project uses a content-based recommendation approach.
Instead of using ratings or user data, it recommends movies based on their similarity in content.
Steps followed:


Selected important features like genres and overview


Combined them into a single text column called “tags”


Converted text data into numerical form using CountVectorizer


Calculated similarity between movies using cosine similarity


Recommended top 5 similar movies based on similarity score



-Tech Stack


Python


Pandas (for data handling)


Scikit-learn (for vectorization and similarity calculation)



-Result
The system successfully recommends 5 movies similar to the input movie.
Example:

Enter a movie name: Titanic
Captain Phillips
Raise the Titanic
The Curious Case of Benjamin Button
The Switch
Code 46

-What I Learned


Basics of working with datasets using Pandas


How text data can be converted into numerical form


Concept of similarity in machine learning


How recommendation systems work at a basic level





