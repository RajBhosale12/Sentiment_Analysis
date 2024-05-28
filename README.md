# Sentiment Analysis on US Airline Reviews

This project performs sentiment analysis on US airline reviews using a Long Short-Term Memory (LSTM) network. The dataset used contains tweets about various airlines and their respective sentiments.

## Dataset

The dataset used is `Tweets.csv`, which contains the following columns:

- `tweet_id`
- `airline_sentiment`
- `airline_sentiment_confidence`
- `negativereason`
- `negativereason_confidence`
- `airline`
- `airline_sentiment_gold`
- `name`
- `negativereason_gold`
- `retweet_count`
- `text`
- `tweet_coord`
- `tweet_created`
- `tweet_location`
- `user_timezone`

For this project, we use only the `text` and `airline_sentiment` columns.

## Requirements

- pandas
- matplotlib
- tensorflow
- keras

You can install the required packages using pip:

```bash
pip install pandas matplotlib tensorflow

Steps to Run the Project
Load the Dataset: Upload and load the Tweets.csv file.
Data Preprocessing: Filter out neutral tweets and preprocess the text data.
Tokenization and Padding: Tokenize the text and pad the sequences.
Model Building: Build and compile an LSTM model.
Model Training: Train the model on the preprocessed data.
Evaluation and Visualization: Evaluate the model and visualize the training history.
Prediction: Use the trained model to predict sentiment for new sentences.
Code Overview
