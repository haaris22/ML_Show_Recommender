# ML_Show_Recommender

This project uses the pandas data science stack and sklearn library to complete a show recommender system, using machine learning to return a list of shows recommended related to an inputted show title. The algorithm creates a similarity matrix between each possible show combination in the database and then uses cosine similarity to find the list of shows, for the inputted show which have the highest similarity rating. This similarity rating is based on the similarity of keywords in the shows cast and crew list and the synopsis.
