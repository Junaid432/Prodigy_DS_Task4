# Sentiment Analysis of Twitter Data

This project aims to analyze sentiment patterns in social media data to understand public opinion and attitudes towards specific topics or brands. The dataset used in this analysis is obtained from Kaggle and contains information about entities, sentiment labels, and tweet content.

# Steps Involved:
1 Data Loading: The dataset is loaded into a Pandas DataFrame using the pd.read_csv() function.

2 Preprocessing:

Convert text to lowercase to ensure consistency.
Remove URLs from the tweet content to focus on the text.
Remove special characters and punctuation to clean the text data.
Tokenize the text into individual words.
Remove stop words such as 'the', 'is', 'and', etc., to reduce noise.
Lemmatize words to reduce them to their base form for better analysis.
3 Sentiment Analysis:

Analyze the sentiment distribution by counting the occurrences of each sentiment label (positive, negative, neutral, and mixed).
Visualize the sentiment distribution using a bar plot to understand the overall sentiment trends.
# Tools Used:
Python programming language
Pandas library for data manipulation
NLTK (Natural Language Toolkit) for text preprocessing, tokenization, stop words removal, and lemmatization
Matplotlib library for data visualization
# How to Use:
Download or clone the repository to your local machine.
Install the required dependencies mentioned in the requirements.txt file.
Run the Python script provided in the repository.
Explore the sentiment analysis results and visualizations generated from the Twitter data.
