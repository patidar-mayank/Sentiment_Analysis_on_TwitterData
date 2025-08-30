# Sentiment Analysis on Twitter Data

This project performs sentiment analysis on Twitter data using machine learning techniques. The main objective is to classify tweets about different airlines into sentiments: positive, negative, or neutral. The analysis leverages Python libraries such as pandas, scikit-learn, and matplotlib for data preprocessing, feature extraction, model building, and evaluation.

## Project Overview

Social media platforms like Twitter are rich sources of public opinions and sentiments. This project aims to automatically classify the sentiment of airline-related tweets. The workflow includes data cleaning, text preprocessing, feature extraction with TF-IDF, model training (Logistic Regression), and evaluation.

## Dataset

The dataset used in this project is a collection of tweets about US airlines, with each tweet labeled as `positive`, `negative`, or `neutral`. The data contains the following columns (after cleaning):

- `text`: The original tweet text.
- `airline_sentiment`: The sentiment label (positive/negative/neutral).

## Workflow

1. **Import Libraries**: pandas, numpy, re, matplotlib, seaborn, scikit-learn.
2. **Load Dataset**: Read the CSV file containing the tweets.
3. **Data Exploration**: Check data shape, columns, and missing values.
4. **Data Cleaning**: Keep only relevant columns and preprocess text (lowercasing, removing URLs, mentions, hashtags, punctuation, numbers).
5. **Feature Extraction**: Convert text into numerical features using TF-IDF vectorization.
6. **Train-Test Split**: Split the data into training and test sets.
7. **Model Training**: Train a Logistic Regression classifier.
8. **Evaluation**: Evaluate the model using accuracy and classification report.

## Requirements

- Python 3.x
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

Install dependencies via pip:

```sh
pip install pandas numpy scikit-learn matplotlib seaborn
```

## How to Run

1. Clone this repository:

    ```sh
    git clone https://github.com/patidar-mayank/Sentiment_Analysis_on_TwitterData.git
    cd Sentiment_Analysis_on_TwitterData
    ```

2. Download the dataset (e.g., `Tweets.csv`) and place it in the working directory.

3. Run the Jupyter Notebook:

    ```sh
    jupyter notebook Sentiment_Analysis_on_Twitter.ipynb
    ```

 
