#  Task 2: Sentiment Analysis using TF-IDF & Logistic Regression

##  Objective

This task aims to build a sentiment analysis model that classifies customer reviews into positive or negative sentiments. It uses Natural Language Processing (NLP) techniques such as text preprocessing and TF-IDF vectorization, followed by Logistic Regression for classification. The dataset contains iPhone product reviews and numeric ratings, which are converted into binary sentiment labels. This task demonstrates how to extract useful insights from textual data for decision-making and product improvement.

##  Dataset

- **File**: `iphone.csv`
- **Text Column**: `reviewDescription`
- **Label Column**: `ratingScore`
- Ratings of 4–5 are labeled **positive**, 1–2 as **negative**, and 3 as **neutral** (removed).

##  Technologies Used

- Python
- Jupyter Notebook
- pandas, matplotlib, seaborn
- scikit-learn (LogisticRegression, TfidfVectorizer)

## Steps Performed

1. Loaded and explored the dataset (`iphone.csv`).
2. Converted ratings into sentiment labels.
3. Cleaned the review text: removed punctuation, lowered case, removed stopwords.
4. Transformed text using TF-IDF (Term Frequency-Inverse Document Frequency).
5. Trained a Logistic Regression classifier.
6. Evaluated using accuracy, classification report, and confusion matrix.

##  How to Run

```bash
jupyter notebook sentiment_analysis.ipynb
```

Ensure `iphone.csv` is in the same directory.

## Output

- Accuracy score
- Classification report (precision, recall, F1)
- Confusion matrix heatmap
- ![image](https://github.com/user-attachments/assets/4bae455f-026b-43fc-b9da-87348a0b4562)


## Summary

This task shows how to turn customer feedback into structured insights. By using Logistic Regression on TF-IDF-transformed data, we built a simple yet effective binary sentiment classifier. The methods here form the foundation for larger NLP tasks such as spam detection or review summarization.
