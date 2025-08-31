Objective: Classify SMS messages as spam or ham using NLP and machine learning.

Dataset: SMS Spam Collection Dataset (5,574 labeled messages from Kaggle).

Workflow: Load and preprocess text (lowercasing, punctuation/stopword removal), convert to numeric features with TF-IDF, train a Naive Bayes model, evaluate with Accuracy/Precision/Recall/F1, and test with custom messages.

Requirements: pandas, numpy, matplotlib, seaborn, scikit-learn, nltk.

Output: ~97–99% accuracy with predictions like “Congratulations! You won a free ticket” → Spam and “Hey, are we still meeting for lunch?” → Ham.
