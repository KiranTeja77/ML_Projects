#  Task 4: Movie Recommendation System (Item-Based Filtering)

## Objective

This task involves building a simple recommendation system using collaborative filtering. The model uses item-based cosine similarity to recommend movies that are similar to a given one based on user ratings. It avoids external dependencies like `scikit-surprise` and uses Pandas and scikit-learn instead.

##  Dataset

- **File**: `ratings.csv`
- **Columns**: `userId`, `movieId`, `rating`
- Small mock dataset simulating user-movie interactions.

##  Technologies Used

- Python
- pandas
- scikit-learn (cosine_similarity)

## Steps Performed

1. Loaded ratings data into a Pandas DataFrame.
2. Built a user-item matrix (users as rows, movies as columns).
3. Calculated cosine similarity between items (movies).
4. Created a function to recommend top 5 similar movies to a given `movieId`.

##  How to Run

```bash
jupyter notebook recommendation_system.ipynb
```

Ensure `ratings.csv` is in the same folder.

##  Output

- List of top 5 similar movies for a given movie ID
- Cosine similarity scores

##  Summary

This task demonstrates a fundamental item-based collaborative filtering technique for building a recommender system. It’s lightweight, interpretable, and forms the basis for more advanced methods like matrix factorization or neural recommender systems.
