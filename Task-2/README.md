# 💬 Task 2: Sentiment Analysis with TF-IDF & Logistic Regression

## 📌 Objective
Perform sentiment classification on iPhone customer reviews using **TF-IDF Vectorization** and **Logistic Regression**.

## 📂 Dataset
- `iphone.csv` (contains `reviewDescription` and `ratingScore` columns)

## ⚙️ Technologies Used
- Python
- scikit-learn
- pandas
- matplotlib
- seaborn

## 🧪 Steps Performed
1. Sampled 1000 reviews from the dataset to optimize performance.
2. Converted `ratingScore` into sentiment labels:
   - Ratings 4–5 → Positive
   - Ratings 1–2 → Negative
   - Rating 3 → Neutral (removed)
3. Transformed review text (`reviewDescription`) using TF-IDF vectorizer.
4. Trained a Logistic Regression model using the `saga` solver.
5. Evaluated the model using accuracy, classification report, and confusion matrix.

## ▶️ How to Run
```bash
jupyter notebook sentiment_analysis_iphone.ipynb
```

## 📊 Output
![sentiment_analysis](https://github.com/user-attachments/assets/96edde9a-35cf-46ac-a368-a0cf14810740)

