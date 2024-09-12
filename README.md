# Sentiment-analysis-with-tweets

Project Overview:

This project involves performing sentiment analysis on tweets using the Sentiment140 dataset. The main objectives were to preprocess the text data, vectorize the text using TF-IDF, train a logistic regression model for sentiment classification, and evaluate the model's performance.

Key Steps and Techniques:

    Data Acquisition and Preparation:
        Dataset: Downloaded the Sentiment140 dataset from Kaggle.
        Extraction: Unzipped the dataset and loaded it into a pandas DataFrame.
        Preprocessing: Applied text preprocessing techniques including stemming and removal of stopwords to clean the text data.

    Text Vectorization:
        Utilized TF-IDF (Term Frequency-Inverse Document Frequency) vectorizer to convert the text data into numerical features suitable for machine learning algorithms.

    Model Training:
        Algorithm: Implemented Logistic Regression as the classification algorithm.
        Training: Trained the model on the preprocessed and vectorized text data.

    Model Evaluation:
        Training Accuracy: Achieved an accuracy score of 81.02% on the training data, indicating how well the model fits the training dataset.
        Testing Accuracy: Achieved an accuracy score of 77.74% on the test data, reflecting the model's performance on unseen data.

    Model Persistence:
        Saved the trained model using pickle for future predictions and reusability.
        Future Predictions: Demonstrated the model's prediction capabilities on individual samples from the test set.


**Results:**

- **Training Accuracy**: 0.81018984375 %
- **Testing Accuracy**: 0.77741875 %

project link :https://colab.research.google.com/drive/1zQqOLLUpizC83XhQZ4fUdw7phu0zNq3l?usp=sharing

The model was able to effectively classify tweets into positive and negative sentiments, with a training accuracy of 81.02% and a testing accuracy of 77.74%. This indicates robust performance on both the training and testing datasets.
