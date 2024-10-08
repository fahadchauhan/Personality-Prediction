# Personality Prediction

The goal of this project was to predict personality traits from social media posts based on the Big Five personality characteristics: Extraversion, Agreeableness, Openness, Conscientiousness, and Neuroticism. Using a custom dataset containing text data from social platforms like Facebook and Twitter, we performed extensive data preprocessing that involved tokenization, stopword removal, lemmatization, and filtering. The project employed TF-IDF to compute term frequencies and document frequencies and leveraged an emotion lexicon to derive sentiment tendencies.

An unsupervised learning approach was used to analyze the text data and predict the personality traits. By utilizing features from the emotion lexicon, we aligned the words with corresponding personality traits. This analysis helped determine the dominant personality traits of each user based on their social text interactions. The final personality classifications were achieved using techniques like Gaussian Naive Bayes for validation.

The system successfully predicted personality traits from the unsupervised data, classifying individuals into one of the five key personality characteristics. The results demonstrated meaningful alignment between text data and inferred personality types, revealing patterns that accurately identified tendencies like Openness, Conscientiousness, and Neuroticism.
