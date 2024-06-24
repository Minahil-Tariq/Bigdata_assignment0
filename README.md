# Bigdata_assignment0

This project involves processing and analyzing review data from a JSON file containing reviews for cell phones and accessories. The script performs the following tasks:

1) Loading and exploring the dataset.
2) Filtering the dataset to retain necessary columns.
3) Preprocessing the review text.
4) Conducting thematic and sentiment analysis.


Exploring and Filtering the Data


The explore_and_filter function:
Loads the data.
Prints the structure of the dataset, including the number of entries and an example entry.
Filters the dataset to retain only the necessary columns: reviewerID, reviewerName, reviewText, and overall.
Preprocessing the Text
The preprocess_text function:


Removes punctuation.
Converts text to lowercase.
Removes stop words and short words (less than three characters).
The example input_text is processed and printed.
Thematic Analysis
The thematic_analysis function:


Loads the data.
Separates reviews into positive (ratings >= 4) and negative (ratings <= 2).
Preprocesses the review texts.
Tokenizes the reviews.
Performs frequency analysis to identify the most common words in positive and negative reviews.
The top 10 words in positive and negative reviews are printed.
Thematic and Sentiment Analysis
The thematic_and_sentiment_analysis function:


Loads the data.
Separates reviews into positive and negative based on ratings.
Preprocesses the review texts.
Tokenizes the reviews.
Performs frequency analysis.
Defines word weights for sentiment analysis and calculates sentiment scores for positive and negative reviews.
Prints the top words, sentiment scores, and overall sentiment for positive and negative reviews.
