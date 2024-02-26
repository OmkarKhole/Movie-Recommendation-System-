# Movie-Recommendation-System Using Python - Project
This project implements a movie recommendation system using machine learning techniques in Python. It aims to predict movies that users might enjoy based on their past preferences or the interests of similar users.
Key Features:
Dataset: Utilizes a dataset of 4803 movies with many features like title,cast,director,genres,keywords,tagline,popularity,etc.but mainly focused on 'genres','keywords','tagline','cast','director'
Libraries Used:
pandas (pd): For data manipulation and analysis.
numpy (np): For numerical operations and array handling.
difflib: For identifying similar movies using string comparison algorithms (optional, but could be incorporated for more comprehensive recommendations).
sklearn.feature_extraction.text.TfidfVectorizer:Converting text to vectors to create a TF-IDF vector representation of movie descriptions, capturing their semantic relationships.
sklearn.metrics.pairwise.cosine_similarity: To calculate the cosine similarity between movie vectors, identifying movies with similar descriptions and potentially similar user preferences.
