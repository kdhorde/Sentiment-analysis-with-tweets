# Sentiment-analysis-with-tweets

**Project Overview:**

This project involves performing sentiment analysis on tweets using the Sentiment140 dataset. The main objectives were to preprocess the text data, vectorize the text using TF-IDF, train a logistic regression model for sentiment classification, and evaluate the model's performance.

**Key Steps and Techniques:**

1. **Data Acquisition and Preparation:**
   - **Dataset**: Downloaded the Sentiment140 dataset from Kaggle.
   - **Extraction**: Unzipped the dataset and loaded it into a pandas DataFrame.
   - **Preprocessing**: Applied text preprocessing techniques including stemming and removal of stopwords to clean the text data.

2. **Text Vectorization:**
   - Utilized TF-IDF (Term Frequency-Inverse Document Frequency) vectorizer to convert the text data into numerical features suitable for machine learning algorithms.

3. **Model Training:**
   - **Algorithm**: Implemented Logistic Regression as the classification algorithm.
   - **Training**: Trained the model on the preprocessed and vectorized text data.

4. **Model Evaluation:**
   - **Training Accuracy**: Achieved an accuracy score of [Training Accuracy] on the training data, indicating how well the model fits the training dataset.
   - **Testing Accuracy**: Achieved an accuracy score of [Testing Accuracy] on the test data, reflecting the model's performance on unseen data.

5. **Model Persistence:**
   - Saved the trained model using pickle for future predictions and reusability.
   - **Future Predictions**: Demonstrated the model's prediction capabilities on individual samples from the test set.

**Results:**

- **Training Accuracy**: 0.81018984375 %
- **Testing Accuracy**: 0.77741875 %
project link :https://colab.research.google.com/drive/1zQqOLLUpizC83XhQZ4fUdw7phu0zNq3l?usp=sharing

The model was able to effectively classify tweets into positive and negative sentiments, with the accuracy indicating robust performance on both the training and testing datasets. 

