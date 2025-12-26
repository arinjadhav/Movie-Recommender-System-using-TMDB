<!-- PROJECT LOGO -->
![20d38e00-6634-11eb-9d1f-6a5232d0f84f](https://user-images.githubusercontent.com/86877457/132905471-3ef27af4-ecc6-44bf-a47c-5ccf2250410c.jpg)

## Movie Recommender System using TMDB
A content-based movie recommendation system built using the TMDB dataset. The system leverages cosine similarity to recommend movies based on features like genres, keywords, and cast/crew information. Users can input a movie, and the model suggests similar movies based on their preferences.

## Table of Contents

1.	Cosine Similarity Overview:
Cosine Similarity is a metric used to measure the similarity between two documents or vectors. It calculates the cosine of the angle between them.
2.	Vector Representation:
To demonstrate Cosine Similarity, we first need vector representations. In this implementation, vectors are represented as NumPy arrays.
3.	Using cosine_similarity():
Once we have the vectors, the cosine_similarity() function can be called with the two vectors as input. It computes the similarity score between them.
4.	Similarity Score Range:
The result is a value between 0 and 1:
0: Completely different vectors.
1: Completely similar vectors.

6.	Learn More
For additional details, visit this guide on Cosine Similarity.
