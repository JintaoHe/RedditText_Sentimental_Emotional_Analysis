# Wall Street Reddit Project

## Introduction

This project analyzes discussions on Wall Street-themed Reddit forums to extract insights into stock market sentiment. It focuses on understanding the collective behavior of Reddit users and their potential impact on financial markets.

## Project Parts

- **Data Exploration**: Scripts for scraping Reddit posts and comments from specified time frames.
- **Data Cleaning**: Procedures to preprocess the raw data for analysis, such as removing special characters, stop words, and irrelevant content.
- **Applying different DTMs: Discover the Most Frequent Words**: Use different types of Vectorizer to tokenize the text, including Traditional Vectorizer, TFIDF Vectorizer, Binary Vectorizer, Vector Normalization L1, Vector Normalization L2, and N-Gram. Also, building the visualizations for all the Vectorizer's results, including Bar Charts, Word Cloud Visualization
- **Sentimental & Emotional Analysis**: Implement different sentiment analyses on the cleaned data to determine the general sentiment (positive, negative, neutral), including VADER, TextBlob, and AFINN, and generate the visuals based on the result. The additional analysis includes the Time series of the data distribution and Emotion Analysis.  
- **Download GME and AMC Stock Price Data from Yahoo Finance**: Use Yahoo API to download the stock data, including stock data download, ETL, and visualizations  
- **Analyze the Relationship between Comments and AMC & GME Stock Price Data**: Analyze the stock performance regarding the comments in Reddit.
- **Machine Learning Prediction on Return Index**: Various Machine learning models use Sentimental and emotional Analysis to predict the stock return index. The model includes Logistic Regression and XGBoost

## Technologies/Libraries Used

- `Python`: Primary programming language used.
- `Jupyter Notebook`: For interactive development and visualizations.
- `sklearn`: Machine Learning models.
- `xgboost `: XGBClassifier.
- `pandas`: Data manipulation and analysis.
- `NumPy`: Numerical computations.
- `NLTK`: Natural Language Toolkit for text processing and sentiment analysis.
- `matplotlib` & `seaborn`: Data visualization.

## Highlights of the Project

- Effective use of Reddit's comments for extensive content collection.
- A comprehensive data cleaning pipeline ensuring data quality and accuracy for analysis.
- Sentiment analysis to understand the Wall Street Reddit community's mood and opinions, providing market movement insights.
- Detailed visualizations that depict sentiment trends and highlight the most discussed stocks and topics.
- Machine Learning model that uses sentiment analysis to predict stock performance. 

