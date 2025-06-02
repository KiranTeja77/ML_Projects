# 🎯 Task 4: Movie Recommendation System

## 📌 Objective
Build a **Recommendation System** using **Collaborative Filtering (SVD)** with the **MovieLens 100k** dataset.

## 📂 Dataset
- `u.data` from [MovieLens 100k](https://grouplens.org/datasets/movielens/100k/)
- Format: `userID itemID rating timestamp`

## ⚙️ Technologies Used
- Python
- scikit-surprise

## 🧪 Steps Performed
1. Loaded dataset using `surprise` library.
2. Trained a matrix factorization model using SVD.
3. Evaluated performance using RMSE.
4. Generated top-N recommendations for users.

## ▶️ How to Run
```bash
jupyter notebook recommender.ipynb
```

## 📊 Output
- RMSE score
- List of top 5 movie recommendations for selected users
