# Supervised-Learning-models-and-Boosting-on-Donors-choose-Dataset

To assist DonorsChoose in making funding approval decisions, I Applied a Decision Tree Classifier and Gradient Boosted Decision Tree Classifier
on two different feature sets:

Set 1: Categorical and numerical features + preprocessed_essay (TFIDF) + Sentiment scores (preprocessed_essay)
Set 2: Categorical and numerical features + preprocessed_essay (TFIDF W2V) + Sentiment scores (preprocessed_essay)
Conducted hyperparameter tuning using k-fold cross-validation to find the best hyperparameters, specifically:

max_depth in the range [1, 5, 10, 50]
min_samples_split in the range [5, 10, 100, 500]
Plotted the performance of the model on both train data and cross-validation data for each hyperparameter using a 3D scatter plot or a heatmap.

Identified the best hyperparameters that gave the maximum AUC (Area Under the ROC Curve) value.

Trained the model using the best hyperparameters and evaluated its performance on the test data. Plotted the ROC curve on both the train and test data and printed the confusion matrix with predicted and original labels of the test data points.

Extracted the false positive data points from the confusion matrix.

Plotted a WordCloud with the words from the essay text of the false positive data points.

Plotted a box plot with the price of the false positive data points.

Plotted a probability density function (PDF) with the teacher_number_of_previously_posted_projects of the false positive data points.

For Task 2, considered Set 1 features only and selected the features with non-zero feature importance.

![DT](https://github.com/Anubis997/Supervised-Learning-models-and-Boosting-on-Donors-choose-Dataset/assets/96742087/4fc26f79-fb72-4987-b113-baee64153c78)

![GBDT](https://github.com/Anubis997/Supervised-Learning-models-and-Boosting-on-Donors-choose-Dataset/assets/96742087/e96f2f84-0cda-44f6-b5d8-beb49e543b97)




Applied a chosen model (Decision Tree, Logistic Regression, or Linear SVM) after discarding the remaining features.

Performed hyperparameter tuning for the selected models


