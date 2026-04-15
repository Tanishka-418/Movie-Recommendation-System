# Movie-Recommendation-System

🚀 Movie Recommendation System

A content-based movie recommendation system that suggests similar movies based on user input using machine learning techniques.

📌 Overview

This project aims to replicate how platforms like Netflix recommend movies by analyzing the content of movies. When a user enters a movie name, the system recommends a list of similar movies based on their genres and descriptions.

🎯 Objective
To build a recommendation system using content-based filtering
To understand how similarity between items can be used for recommendations
To apply basic machine learning concepts to a real-world problem

📊 Dataset

The project uses the TMDB 5000 Movies dataset from Kaggle.

Features used:
Title – Name of the movie
Genres – Categories of the movie
Overview – Short description of the movie

Only these relevant columns were used to build the model.

⚙️ Approach

This system is based on a content-based filtering approach, where recommendations are made by finding similarities between movies.

Steps involved:
Combined genres and overview into a single text feature
Converted text data into numerical format using vectorization
Calculated similarity between movies using cosine similarity
Retrieved top 5 similar movies based on similarity score

🧠 How It Works
User enters a movie name
The system searches for the movie in the dataset
It compares the selected movie with all other movies
Returns the top 5 most similar movies

📈 Example Output

Input:

Titanic

Output:

- Romeo + Juliet  
- The Notebook  
- Pearl Harbor  
- A Walk to Remember  
- The Great Gatsby  

🛠️ Tech Stack
Python
Pandas
Scikit-learn
VS Code (development environment)

💡 Key Learnings
Understanding how recommendation systems work
Converting text data into numerical form (vectorization)
Using cosine similarity to measure similarity
Applying machine learning concepts to real-world applications

🚀 Future Improvements
To add collaborative filtering for better recommendations
To build a web interface using Flask or Streamlit
To Improve recommendations using more features (cast, director, etc.)

📎 How to Run the Project
Clone the repository:
git clone https://github.com/Tanishka-418/Movie-Recommendation-System.git
Install dependencies:
pip install pandas scikit-learn
Run the Python file:
python app.py
Enter a movie name and get recommendations 🎬

🙌 Conclusion

This project demonstrates how machine learning can be used to build intelligent systems that enhance user experience by providing personalized recommendations.





