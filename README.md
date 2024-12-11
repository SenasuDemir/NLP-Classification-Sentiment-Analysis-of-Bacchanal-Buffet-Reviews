# NLP-Classification-Sentiment-Analysis-of-Bacchanal-Buffet-Reviews

## Introduction
The goal of this project is to improve services and customer satisfaction for Bacchanal Buffet by analyzing customer reviews from various platforms such as Yelp, Foursquare, and Twitter. We will perform sentiment analysis using Natural Language Processing (NLP) techniques to provide insights and suggestions.

### Business Need
To enhance the customer experience at Bacchanal Buffet, it is crucial to analyze customer feedback and identify areas for improvement. By analyzing customer sentiments from multiple data sources, we can better understand customer preferences and pain points.

### Objectives
- Perform **NLP Supervised Classification** on the Yelp dataset.
- Implement **Sentiment Analysis** on Yelp reviews.
- Scrape the **Foursquare dataset** and perform sentiment analysis.
- **Get Tweets** about Bacchanal Buffet and analyze sentiment.
- Compare the results of sentiment analysis across platforms.

## Data Analysis & Visualization
In this step, we will:
- Load and explore the dataset.
- Perform basic data cleaning (removing unnecessary characters, handling missing data).
- Visualize the data to understand trends and patterns in customer feedback.

## Language Detection
Before applying sentiment analysis, we will detect the language of the reviews and filter out any non-English reviews to focus on relevant data.

## Data Preprocessing
Steps include:
- **Removing special characters** and unnecessary text from the reviews.
- **Tokenization**: Breaking down reviews into words or tokens.
- **Calculating polarity and subjectivity**: Analyzing sentiment strength and subjectivity of reviews.
- **Creating a WordCloud**: Visualizing the most frequent words in positive and negative reviews.
- **Applying Lemmatization**: Reducing words to their base forms.

## Classification Steps
We will train machine learning models to classify the sentiment of reviews based on labeled data.

### Models Used and Accuracy

| Model                        | Accuracy  |
|------------------------------|-----------|
| Logistic Regression           | 81.06%    |
| Gradient Boosting Classifier  | 78.17%    |
| AdaBoost Classifier           | 76.72%    |
| Random Forest Classifier      | 70.27%    |
| Decision Tree Classifier      | 69.20%    |
| Bernoulli Naive Bayes         | 67.13%    |
| Multinomial Naive Bayes       | 67.13%    |


## Conclusion
This analysis aims to provide actionable insights for Bacchanal Buffet by understanding customer sentiments. The classification models performed well, with Logistic Regression yielding the highest accuracy.
