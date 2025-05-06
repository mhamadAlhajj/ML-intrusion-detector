Classification Model with Preprocessing and Decision Tree
This project implements a classification pipeline using Decision Tree Classifier along with data preprocessing steps for handling numeric and categorical features.

Project Overview
----------------
Preprocessing: The pipeline applies a log transformation to numeric features and one-hot encoding to categorical features.
Model: A Decision Tree Classifier is used for classification.


Pipeline Details
----------------
Preprocessing:
Numeric features are transformed using a log1p transformation to handle skewed distributions.
Categorical features are one-hot encoded.

Model:
Decision Tree Classifier is trained on the preprocessed dataset.
