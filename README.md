# SENTIMENT-ANALYSIS-OF-TWITTER-TO-DECIPHER-AND-DETECT-OFFENSIVE-SPEECH 
Sentiment Analysis has become essential business wise as well as socially so as to analyze how millions of people take in the information and changes happening around the world and how it affects their lives. With growing popularity of social media and the anonymity and convenience it offers, has led to an increase in hate speech, therefore, there is an urgent need for effective solutions.

In our project we will perform sentiment analysis on twitter and detect the hate speech on tweets by using machine learning models. Twitter is an information network and communication mechanism that produces more than millions of tweets a day. The Twitter platform offers access to that corpus of data, via the APIs. Each API represents a facet of Twitter, and allows developers to build upon and extend their applications in new and creative ways. The Twitter API allows one to access the features of Twitter without having to go through the website interface. This can be useful for doing things like posting tweets or sending directed messages in an automated way with scripts. So, we will be using the twitter dataset which will be extracted from twitter API using an extractor and then carry out the methodologies and perform the ML algorithms.

# Objective:
There are around 500 million messages and posts created on the platform daily and thus the job of filtering toxic content and offensive language is a difficult task. Due to the ongoing battles with hate speech which include dialogues related to sexism, racism, etc. we intend to decipher what can be classified to be hate speech and what cannot be.

➢ Our project aims to detect offensive speech in order to prevent the spreading of hate/toxic content over social media.

➢ Our project, thus will be helpful to act as a surveillance system so as to keep a check on the offensive messages/tweets on twitter.

➢ So, in this project, we plan to create a system using a learning approach to automatically classify tweets on Twitter into offensive speech and non-offensive.

# Methodology:
1. The first step of building our model was to balance the number of hate and non-hate tweets.
2. We clean the tweets by employing lemmatization, stemming, removal of stop words, and omissions.
3. Then for the pre-processing step, we use Bag of words and Term Frequency Inverse Document Frequency (TFIDF). 
4. For both the Bag of words and TFIDF, we run 5 classification algorithms, namely Logistic Regression, Naive Bayes, Decision Tree, Random Forest and Gradient Boosting.
5. These 5 algorithms are run again after performing dimensionality reduction for both TF-IDF and Bag of Words.

Our goal is to classify tweets into two categories, hate speech or non-hate speech. Our project analyzed a dataset CSV file from Kaggle containing 31,935 tweets. The dataset was heavily skewed with 93% of tweets or 29,695 tweets containing non-hate labeled Twitter data and 7% or 2,240 tweets containing hate-labeled Twitter data. The first step of building our model was to balance the number of hate and non-hate tweets. Our data preprocessing step involved 2 approaches, Bag of words and Term Frequency Inverse Document Frequency (TFIDF). The bagof-words approach is a simplified representation used in natural language processing and information retrieval. In this approach, a text such as a sentence or a document is represented as the bag (multiset) of its words, disregarding grammar and even word order but keeping multiplicity. TFIDF is a numerical statistic that is intended to reflect how important a word is to a document in a collection. It is used as a weighting factor in searches of information retrieval, text mining, and user modeling. Before we input this data into various algorithms, we have to clean it as the tweets contain many different tenses, grammatical errors, unknown symbols, hashtags, and Greek characters. 
