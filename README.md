# Deep Learning Week 4: NLP Disaster Tweets Kaggle Mini-Project

## 1. Project Overview

In this week assignment, we'll participate in the Kaggle [NLP Disaster Tweets](https://www.kaggle.com/competitions/nlp-getting-started) Challenge. We'll build DL models to predict which Tweets are about real disasters and which ones are not based on the Tweet content. For this week assignment, we'll focus on RNN (Recurrent Neural Network) models.

#### About the Dataset

We will be using the  Kaggle [NLP Disaster Tweets](https://www.kaggle.com/competitions/nlp-getting-started) dataset. The dataset is provided subjected to Kaggle [Competition Rules](https://www.kaggle.com/competitions/nlp-getting-started/rules#7-competition-data).

**Files**

- train.csv - the training set
- test.csv - the test set
- sample_submission.csv - a sample submission file in the correct format

**Columns**

- id - a unique identifier for each tweet
- text - the text of the tweet
- location - the location the tweet was sent from (may be blank)
- keyword - a particular keyword from the tweet (may be blank)
- target - in train.csv only, this denotes whether a tweet is about a real disaster (1) or not (0).

#### Summary of Tasks:
- Load dataset
- Explore the dataset, perform data cleaning, data analysis, preprocess data
- Build and test models: Build, evaluate, and compare model's performances. 
- Summarize and discuss the results.
