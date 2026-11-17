**Movie Preference Prediction Using Machine Learning**

**Project Overview**

This project uses machine learning to predict whether a user will like a movie based on their previous ratings and movie information.

**Dataset**

Dataset: MovieLens Latest Small

Ratings: 100,836

Users: 610

Movies: 9,742

Rating scale: 0.5-5.0

Movies rated 4.0 or higher are classified as Like (1), and ratings below 4.0 are classified as Not Like (0).

**Features**

Four features are used for prediction.

-User average rating

-Movie average rating

-Movie popularity (with number of ratings)

-User genre preference

**Machine Learning Models**

-Logistic Regression

-Decision Tree

-Gaussian Naive Bayes

-Decision Tree with maximum depth of 5

**Preliminary Results**

Three machine learning algorithms were trained and evaluated using accuracy, precision, recall, and F1-score. Logistic Regression achieved the highest accuracy at 71.14%. Navie Bayes at 69.93%. Decision Tree at 63.95%. After limiting the Decision Tree's maximum depth to 5, its accuracy improved to 70.78%, and it reduced overfitting and producing better test results. Overall, Logistic Regression performed best in terms of accuracy, and Decision Tree achieved a slightly higher F1-score.

**Dataset Source and Reference**

This project uses the **MovieLens Latest Small** dataset provided by GroupLens Research at the University of Minnesota.

Dataset: https://grouplens.org/datasets/movielens/

Reference:

Harper, F. M., & Konstan, J. A. (2015). The MovieLens datasets: History and context. *ACM transactions on Interactive Intelligent Systems, 5*(4), Article 19.
https://dl.acm.org/doi/10.1145/2827872
