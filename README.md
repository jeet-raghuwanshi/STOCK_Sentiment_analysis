# STOCK_Sentiment_analysis

In this stock sentiment analysis project, the objective is to predict stock market trends based on news headlines. A dataset containing stock news headlines from Kaggle was used to create a machine learning model in Python. To acquire new data for testing the model, the Selenium library was employed to scrape the web for current news headlines. Two algorithms, Random Forest and Naive Bayes, were applied to build the models for sentiment analysis.

The project can be divided into the following steps:

1. Data Acquisition: The stock news headlines dataset was obtained from Kaggle, and additional data was collected using web scraping with Selenium.

2. Data Preprocessing: The data was cleaned and preprocessed, including text normalization, tokenization, and removal of stopwords, to prepare it for machine learning algorithms.

3. Feature Extraction: Techniques such as Bag of Words, TF-IDF, or word embeddings were applied to transform the text data into numerical feature vectors suitable for machine learning models.

4. Model Building: The Random Forest and Naive Bayes algorithms were applied to train the sentiment analysis models on the preprocessed data. These models were then evaluated based on their performance metrics, such as accuracy, precision, recall, and F1-score.

5. Model Testing: The trained models were tested on the newly collected data obtained through web scraping. This step helped to assess the model's performance on real-world data and understand its practical applicability.

In conclusion, this project demonstrates the use of machine learning algorithms in sentiment analysis to predict stock market trends based on news headlines. The implementation of the Random Forest and Naive Bayes algorithms, along with the Selenium library for web scraping, showcases the potential of combining machine learning and web data for financial analysis and decision-making.
