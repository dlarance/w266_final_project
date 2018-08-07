# w266_final_project
Final project repository for David Larance and Matthew Prout

## Files

### Amazon Fine Food Reviews Model

The Amazon reviews sentiment classification model:
+ BinaryClassification_AmazonReviews.ipynb

The Amazon reviews sentiment classification model that includes the summary text in the model:
+ BinaryClassification_AmazonReviews2.ipynb

The Amazon reviews sentiment classification model that supports common spelling correction:
+ BinaryClassification_AmazonReviews3.ipynb
+ CommonMisspellings.csv

### Test Data Set Testing Notebooks

These notebooks load the model created for the Amazon reviews and test the sentiment classification accuracy of the model with the data sets.

+ BinaryClassification_IMDB_Reviews.ipynb
+ BinaryClassification_ratebeer_Reviews.ipynb
+ BinaryClassification_yelp_Reviews.ipynb

### EDA

Exploratory data analysis for the Amazon reviews data set:

+ EDA_AmazonReviews.ipynb

### Error Analysis

These .csv files contain a list of mispredicted reviews:

+ Mispredicted_AmazonBinaryClassification.csv
+ Mispredicted_IMDB_Classification.csv
+ Mispredicted_ratebeer_Classification.csv
+ Mispredicted_yelp_Classification.csv

## Folders

### common

Common Python classes

### data_prep

Contains the following:

+ Notebooks that format the different reviews into .csv files
+ EDA notebook for RateBeer
+ Naive Bayes notebook to generate a baseline for the different review data sets
+ csv files for the different data sets

### NaiveBayes

Naive Bayes baseline model

### NBOW

Neural Bag-of-words baseline model
