# Google Playstore Sentiment Modeling

This repository was made by me of one of my project at Kampus Merdeka - Independent Study at Bisa AI. I uploaded the data and my experiment .ipynb file here, so everybody could view this.



# Natural Language Processing 

Natural language processing (NLP) is a branch of artificial intelligence that deals with interactions between computers and humans using natural language, one application is Sentiment Analysis. Sentiment analysis is one of the fields of Natural Language Processing (NLP) which builds a system to recognize and extract opinions in text form. Information in the form of text is currently widely available on the internet in the format of forums, blogs, social media, and sites containing reviews. The goal is to get opinions from users on the platform.

# Dataset 
Open datasets that could be access from kaggle. There's a link to get there: https://www.kaggle.com/datasets/lava18/google-play-store-apps

# Text Processing
1. Lowercase & Removing

   Lowercase for convert a word to lower case, while removing is for remove special characters
   
2. Tokenizing & Stopwords

   Tokenization for breaks the raw text into words, sentences called tokens. These tokens help in understanding the context or developing the model for the Natural Language Processing. Stopwords are used to eliminate unimportant words, allowing applications to focus on the important words instead. For example: in English, “the”, “is” and “and”, would easily qualify as stop words
3. Lemmatization
  
  Lemmatization usually refers to doing things properly with the use of a vocabulary and morphological analysis of words. A lemma (plural lemmas or lemmata) is the canonical form, dictionary form, or citation form of a set of words. For example, runs, running, ran are all forms of the word run, therefore run is the lemma of all these words
  
4. Vectorization
  Vectorization is the process of converting text into numerical representation. For this case used Bag of Word
  
  
  # Features and Target
  
#### X = Translated_reviews that using each preprocessing step, and transformed to array

#### y = Sentiment (Positive, Neutral, Negative)
