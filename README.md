This project implements a user-based collaborative filtering movie recommendation system. The goal is to predict ratings for movies a user hasn’t watched yet, based on ratings from users with similar tastes.

The model was built using the MovieLens 100k dataset, with Python, Pandas, and Scikit-learn. User similarity is measured with Cosine Similarity, and recommendations are generated through weighted averages of the nearest neighbors’ ratings.

As future improvements, the system could be extended with a KNN Regressor, item-based filtering, or even an interface for personalized recommendations.
