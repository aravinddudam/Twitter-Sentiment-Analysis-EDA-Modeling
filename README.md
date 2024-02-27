## Twitter-Sentiment-Analysis-EDA-Modeling

## Overview
The project aimed to solve the challenge of sentiment analysis specifically focusing on extracting the portions of tweets that reflect the sentiment expressed. This task, known as sentiment extraction, involves identifying and extracting the words or phrases from a tweet that contribute most significantly to the tweet's overall sentiment.

To accomplish this, the project employed a variety of Python libraries and techniques including natural language processing (NLP) tools like NLTK and spaCy, data manipulation and analysis with pandas and numpy, as well as visualization with matplotlib, seaborn, and Plotly. The project's workflow included data cleaning, exploratory data analysis (EDA), feature engineering, and training a model for sentiment extraction.

## Project Implementation

1. Data Preprocessing and Cleaning: Implemented functions to clean the tweet texts by removing URLs, HTML tags, punctuation, and numbers. Additionally, stop words were removed to focus on the meaningful content of the tweets.
2. Exploratory Data Analysis (EDA): Conducted a thorough analysis to understand the distribution of sentiments across the dataset. Visualizations such as count plots and funnel charts highlighted the balance of sentiments. The EDA phase also included generating meta-features like the number of words in texts and selected texts, which provided insights into the data's characteristics.
3. Feature Engineering: Developed a Jaccard similarity feature to quantify the similarity between the tweet text and the selected text, offering a measure to understand how closely the sentiment words are related to the overall tweet.
4. Model Training: Utilized spaCy's NER (Named Entity Recognition) capabilities to train models capable of identifying sentiment-bearing phrases within tweets. Models were trained separately for positive and negative sentiments to tailor the extraction process to the sentiment's nature.
5. Innovative Visualization: Leveraged word clouds and distribution plots to visualize the most frequent words in tweets and selected texts, providing a clear view of common themes within sentiments.


## Problem Addressed:
The primary problem tackled was the identification of key phrases within tweets that significantly contribute to the sentiment expressed. This is a crucial task in sentiment analysis, especially for applications like brand monitoring, customer feedback analysis, and social media sentiment analysis, where understanding the specific aspects of a service or product that people like or dislike is valuable.


## Methodology:
1. Data Preparation: Loaded and cleaned the dataset to remove unnecessary information and standardize the text.
Analysis and Visualization: Performed EDA to understand data patterns, sentiment distribution, and common words associated with each sentiment.
2. Feature Engineering: Created features such as word counts, Jaccard scores, and word differences to capture the relationship between the tweet and its sentiment-bearing phrases.
3. Model Development and Training: Developed a model using spaCy's NER to predict the sentiment-bearing phrases within tweets. The model training process involved customizing the training data to fit the NER model requirements, iterative training, and model evaluation.


## Conclusion:
This academic project successfully developed a system capable of extracting sentiment-bearing phrases from tweets, providing valuable insights into public opinion on various topics. Through meticulous data analysis, feature engineering, and the application of NLP techniques, the project highlights the potential of machine learning and NLP in enhancing sentiment analysis tasks.