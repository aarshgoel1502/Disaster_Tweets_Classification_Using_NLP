# Disaster_Tweets_Classification_Using_NLP
Disaster tweet classification using NLP (Natural Language Processing) involves identifying and categorizing tweets that discuss disasters or emergencies. This is useful for real-time disaster management, providing timely information, and aiding in rescue operations. Here's a detailed explanation of how this process works:

1. Data Collection
Source: Tweets are collected using kaggleI, often filtered by keywords related to disasters (e.g., "earthquake", "flood", "fire").
Annotation: The collected tweets are annotated (labeled) as relevant (disaster-related) or irrelevant.
2. Preprocessing
Text Cleaning: Remove URLs, mentions (@username), hashtags, punctuations, and special characters.
Tokenization: Split the tweet into individual words (tokens).
Lowercasing: Convert all text to lowercase to ensure uniformity.
Stop Words Removal: Remove common words that don’t contribute to the meaning (e.g., "and", "the").
Stemming/Lemmatization: Reduce words to their base or root form (e.g., "running" to "run").
3. Feature Extraction
Bag of Words (BoW): Represents the text as a collection of word counts.
TF-IDF (Term Frequency-Inverse Document Frequency): Reflects the importance of a word in a tweet relative to the entire dataset.
Word Embeddings: Represents words in continuous vector space. Popular models include Word2Vec, GloVe, and FastText.
4. Model Building
Machine Learning Algorithms: Common algorithms include Logistic Regression , Support Vector Machines (SVM), and Random Forests.
Deep Learning Models: Use architectures like Recurrent Neural Networks (RNN), Long Short-Term Memory (LSTM), 
