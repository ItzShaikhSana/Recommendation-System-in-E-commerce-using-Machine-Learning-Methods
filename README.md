# Recommendation-System-in-E-commerce-using-Machine-Learning-Methods
A recommendation system is a tool that uses a series of algorithms, data analysis and artificial Intelligence (AI) to make recommendations online.
METHODOLOGY
Data Collection 
* Installing & Importing All Libraries
* Dataset Loading : loading data from json file to 
dataframe .
* Data Cleaning : null values handling, data filtering etc.
* Data Visualization (EDA)
* Phase 1 (Text Classification) – text classification on 
review text is not labelled
I. Text Cleaning : cleaning text using nltk.
II. Text Preprocessing: tfidf vectorizer, converting 
categorical to number.
III. Labelling Data using Vader Sentiment Analyzer
IV. Sentiment Analysis Visualization: WordCloud, 
CountPlot
V. Splitting Dataset into Train and Test.
VI. Model Training: AdaBoostClf, RandomForestClf.
VII. Model Evaluation: Confusion Matrix, Classification 
Report.
* Phase 2 (Recommendation)
I. Popularity Based Recommendation of Top 50 
Product.
II. Collaborative Filtering Based Recommender System
using SVD Model(recommend top 5 product based 
on user).
* GUI (Web Application using Flask)
