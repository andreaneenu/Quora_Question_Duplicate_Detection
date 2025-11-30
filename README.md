# Quora Question Duplicate Detection

Dataset used from the Kaggle competition: [Quora Question Pairs](https://www.kaggle.com/c/quora-question-pairs)

In this project, I did the following:

- Addressed the classification of question pairs as duplicates or non-duplicates using NLP.
- Applied preprocessing, TF-IDF vectorization, and Word2Vec to capture inherent semantic similarity.
- Engineered informative features such as word overlap, length difference, and statistical metrics like Cosine similarity, Jaccard similarity, and Levenshtein distance for enhancement.
- Tested various models including Logistic Regression, Linear SVM, and XGBoost; found that the hyperparameter-tuned XGBoost achieved the best performance with the best F1 score of 0.78 and the least Log Loss of 0.362.
