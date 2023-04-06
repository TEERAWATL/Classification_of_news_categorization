# Classification of News Categorization

Classify news articles into different categories using logistic regression.

## Description

This project aims to categorize types of news articles (in Thai) using a logistic regression model.

Usage
Run the main script to execute the project:
news_categorization_mc.ipynb (For model creating) 
news_categorization_md.ipynb (For Model depolying) 

Dependencies
The project requires the following libraries:

numpy
pandas
matplotlib
scikit-learn
Install the dependencies using the following command:

pip install numpy pandas matplotlib scikit-learn


Dataset Preparation
Collect and organize news articles in Thai along with their categories.
Load the dataset using pandas.
Preprocess the text data by removing special characters, stopwords, and tokenizing.
Split the dataset into training and testing sets using train_test_split from scikit-learn.
Feature Extraction
Use the CountVectorizer from scikit-learn to convert the text data into a bag-of-words representation.
Scale and encode the categorical features using StandardScaler, MinMaxScaler, OrdinalEncoder, and OneHotEncoder from scikit-learn.
Model Training
Train a logistic regression model using LogisticRegression or LogisticRegressionCV from scikit-learn.
Train the model using the prepared training set.
Model Evaluation
Evaluate the trained model using the following methods from scikit-learn:

plot_confusion_matrix
classification_report
