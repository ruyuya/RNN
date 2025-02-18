Disaster Tweets Classification using NLP

Introduction

Problem Description:

This project aims to classify tweets as either disaster-related or not. This is a binary classification problem where the goal is to predict whether a given tweet is about a real disaster (e.g., earthquakes, floods, fires) or not. This task is crucial for emergency response systems, where timely and accurate information can save lives.

Dataset:

Train Data: Contains 7,613 tweets with the following columns:
`id`: Unique identifier for each tweet.
`text`: The text of the tweet.
`keyword`: A keyword from the tweet (may be blank).
`location`: The location from where the tweet was sent (may be blank).
`target`: The target label (1 for disaster, 0 for non-disaster).

Test Data: Contains 3,263 tweets with the same columns as the train data, except for the `target` column, which is what we need to predict.

Data Size, Dimension, and Structure
Train Data: 7,613 rows × 5 columns.
Test Data: 3,263 rows × 4 columns.

References: Natural Language Processing with Disaster Tweets. https://www.kaggle.com/c/nlp-getting-started
