# Supervised-Learning-models-and-Boosting-on-Donors-choose-Dataset
•	Engineered four new features using Sentiment Intensity Analyzer on Essay text. Cleaned essay text using NLTK and vectorized it, using TFIDF and TDIDF avg W2V, while OneHotEncoding was used for vectorizing categorical features.
•	Developed a customized function for finding optimal threshold to boost AUC. Decision Trees produced AUC scores
of 0.62 and 0.60 respectively with optimal thresholds after hyper parameter optimization using Randomsearch.
•	Boosted AUC to 0.8 with GBDT with a max_depth of 5 and 100 estimators by encoding categorical features using response coding, and vectorizing Essay text using TFIDF-W2V.
