# Sentiment Analysis of Daraz Reviews using BERT

## Group Members
## Muhammad Ali - F2020-591
## Muhammad Shehryar Sohail - F2020-364
## Asif Ahmad Chaudhry - F2020-533


This project performs sentiment analysis on customer reviews from Daraz, a popular e-commerce platform, using BERT for sequence classification. The project includes data preprocessing, exploratory data analysis, model training, evaluation, and visualization of results.


## Introduction
The aim of this project is to classify the sentiments of Daraz customer reviews into different categories using a BERT-based model. The project covers the following steps:
1. Data loading and preprocessing
2. Exploratory Data Analysis (EDA)
3. Model training using BERT
4. Model evaluation and performance metrics
5. Visualizations

## Work Division
Ali focused on preparing the dataset, fetching reviews manually from different daraz products, or using techniques such as web scrapping to fetch reviews, and manually labeling the sentiment. The preprocessing was also handled by him with techniques such as stemming, toLower and lastly TF-IDF Vectorizer. The dataset was separated to 80% training and 20% testing. Shehryar mainly focused on the BERT architecture, finialising which BERT model works best in our case. With Asif postive approach to deal with data, it was finalised that BERT base uncased works best in this instance. The model training and evalution was upto Shehryar and Asif itself, although they were having trouble when training them so Ali helped them using the idea of going for LabelEncoder which made things alot easier. The visualisation were to deduce the model practability and it turned out pretty good.

## Requirements
To run this project, you need to install the following dependencies:
- pandas
- numpy
- matplotlib
- seaborn
- wordcloud
- nltk
- scikit-learn
- torch
- transformers

You can install these dependencies using the following command:
```bash
pip install pandas numpy matplotlib seaborn wordcloud nltk scikit-learn torch transformers
