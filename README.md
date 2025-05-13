# Detecting-Fake-News-with-BERT-
Built a deep learning classifier to detect fake news headlines using BERT embeddings and a Doc2Vec-based pipeline trained on real and fake news articles (~45k entries).

Preprocessed text data by removing punctuation, lowercasing, lemmatizing, and eliminating stopwords using NLTK.

Trained and compared multiple models using:

    BERT + Fully Connected Neural Network (achieved ~91% accuracy),

    Doc2Vec embeddings + Deep Neural Network (achieved ~87% accuracy),

    Word2Vec embeddings with similarity querying for semantic understanding.

Designed a custom prediction pipeline for new input sentences and saved models using Pickle for deployment.

Visualized word frequencies with WordClouds and title length distribution for data analysis.
