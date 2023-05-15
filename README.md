# Movie-TV-Shows-Recommendation-system

### In this project, I have developed a recommendation system for movies and TV shows. To create this system, I concatenated the datasets of popular streaming services like Netflix, Amazon Prime, Disney Plus, and Hotstar. Then, I used text vectorization and cosine similarity to find similar movies and TV shows based on the user's input movie.

### To be specific, I used CountVectorizer to convert the text data into vectors, which represent the frequency of words in each movie or TV show's description. Then, I used cosine similarity to measure the similarity between the vectors of the input movie and all the other movies and TV shows in the dataset. The top 5 recommendations were selected based on their cosine similarity scores.

### To use the recommendation system, the user can input the title of a movie or TV show they have enjoyed and the system will recommend 5 similar movies or TV shows to watch next.

## Libraries Used

We'll be using the following libraries for this project:

1. pandas: To store and manage data
2. numpy: To handle all the numerical values in the dataset
3. sklearn: To create the recommendation system
4. cosine_similarity from sklearn.metrics.pairwise: To create a cosine similarity matrix


## Project Tasks
The project involves the following tasks:

Import all the required libraries.
Load Movie_data.csv and Movie_Id_Titles.csv in DataFrames.
Join the DataFrames on Movie_ID.
Explore the dataset to understand its dimensions, statistical summary, and the number of ratings given by each user.
Calculate the sparsity of the interaction matrix.
Use cosine similarity to find the similarity among users.
Create a function to give movie recommendations to a user by finding the k most similar users, their average rating of the movies, and the top 10 rated movies.

## Conclusion
This project will help you understand how to create a recommendation system and build an application using the Streamlit library. It involves tasks such as exploring the dataset, calculating the sparsity of the interaction matrix, finding the similarity among users using cosine similarity, and recommending movies to a user based on their similarity with other users.

## Contributing
Contributions are welcome! If you find any issues or have suggestions for improvement, please open an issue or submit a pull request.



