# Movie Recommender System using Nearest Neighbors

## Executive Summary

The objective of this project is to build a movie recommender system using the Nearest Neighbors algorithm. The system recommends movies similar to a given movie based on selected features. A public dataset containing movie details and their genres was used, and can be found here.

The project follows a step-by-step process, which includes data preprocessing, feature extraction, creating the Nearest Neighbors model, defining recommendation functions, and finally testing the recommender system. The output consists of a list of recommended movies based on the selected features.

## Packages Used

pandas
numpy
sklearn

## Process Followed

1. Import the necessary packages.
2. Load the dataset and explore its structure.
3. Preprocess the data by selecting the necessary columns.
4. Extract features from the dataset.
5. Initialize the Nearest Neighbors model with 5 neighbors and the distance metric set to 'euclidean'.
6. Fit the Nearest Neighbors model with the extracted features.
7. Create a function that takes a movie index and returns the indices of the 5 most similar movies.
8. Create a function to recommend movies based on a given movie name.
9. Test the recommender system by providing a movie name.

## Output and Interpretation

The recommender system provides a list of recommended movies similar to the given input movie. The recommendations are based on the similarity between the genres and other features of the movies in the dataset. For example, when the input movie is 'Ex Machina', the system recommends the following movies:

--Gifted
--Stand and Deliver
--Finding Forrester
--A Brilliant Young Mind
--These recommendations are generated because they share similar features with the input movie 'Ex Machina'. This demonstrates that the Nearest Neighbors-based recommender system is working correctly.

## Conclusion

The Nearest Neighbors algorithm was successfully used to build a movie recommender system. This system can recommend movies similar to a given input movie based on the selected features. The output demonstrates the effectiveness of the Nearest Neighbors algorithm in finding similar items, which can be applied to various other recommendation scenarios as well.



