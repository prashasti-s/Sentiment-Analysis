# Sentiment-Analysis
Amazon reviews sentiment analysis - VADER method

Sentiment analysis is the process of determining the emotional tone or sentiment expressed in a piece of text, such as a review, comment, or social media post. It involves using natural language processing (NLP) techniques to analyze the subjective information present in the text and classify it as positive, negative, or neutral.

# About the dataset:

This dataset contains reviews of various food products available on Amazon, encompassing a timeframe of over 10 years. It comprises approximately 500,000 reviews, covering the period up until October 2012. Each review provides essential details such as product information, user information, ratings, and a plain text review. Additionally, the dataset incorporates reviews from diverse categories across Amazon's platform.

We are downloading the data from Kaggle to perform our analysis

**VADER (Valence Aware Dictionary and sEntiment Reasoner)** is a lexicon and rule-based sentiment analysis tool that is specifically designed for sentiment analysis of social media text. It is included in the NLTK (Natural Language Toolkit) library.

VADER sentiment scoring provides a way to quantify the sentiment polarity of a given text. It analyzes the text and assigns sentiment intensity scores to individual words or phrases, as well as to the overall sentiment of the text. The scores range from -1 (extremely negative) to +1 (extremely positive).

I will use the **SentimentIntensityAnalyzer** from the NLTK library. The SentimentIntensityAnalyzer is a class provided by NLTK (Natural Language Toolkit) that performs sentiment analysis on text.

Then use the **polarity_scores()** method of the analyzer to compute the sentiment scores for the given sentence. The resulting scores object will contains four keys: 'neg' (negative), 'neu' (neutral), 'pos' (positive), and 'compound' (compound score, which represents the overall sentiment of the text).

# Conclusion 
We used amazon food reviews dataset to perform sentiment analysis using the VADER model. The accuracy of the model is 75.9%. To improve the results of sentiment analysis we can use roBERTa model.
