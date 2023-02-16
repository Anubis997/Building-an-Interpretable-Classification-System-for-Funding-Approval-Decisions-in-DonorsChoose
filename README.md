# Supervised-Learning-models-and-Boosting-on-Donors-choose-Dataset
●	Task: Predicted the funding outcome of project proposals on the Donors choose platform, a binary classification
task with classes “Funded” and “Not Funded”.
●	NLP Text Processing and Feature Engineering: Four new features were engineered using sentiment analysis on
essay text, which was cleaned and vectorized using TFIDF and TDIDF avg W2V.
●	Approach: Decision Trees and GBDT were used to build predictive models. A customized function was developed
 to find the optimal threshold to boost the AUC score. 
●	Results: The decision trees produced AUC scores of 0.62. GBDT boosted the AUC score to 0.8. This provided a more accurate prediction of funding outcome and decreased the application processing time by 99%.
