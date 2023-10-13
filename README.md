 # **Twitter Sentiment Analysis**

**Overview**
This project is all about understanding Twitter data sentiments. We're building a sentiment analysis model to classify tweets as positive, negative, or neutral. Twitter is a rich source of real-time public opinion, and this README explains how we're doing it step by step.

**Table of Contents**
1-Data Collection
2-Text Preprocessing
3-Feature Extraction
4-Model Selection
5-Model Training
5-Model Evaluation

1.**Data Collection**
We've got our dataset from Kaggle. It's full of tweets, and each one tells us if it's positive, negative, or neutral.

2. **Text Preprocessing**
Twitter data can be messy. We've cleaned it up by:

1-Removing Stopwords
2-Tokenization
3-Lemmatization
4-Stemming

3. **Feature Extraction**
To prepare the text data for machine learning, we used the TF-IDF (Term Frequency-Inverse Document Frequency) technique. TF-IDF assigns numerical values to words based on their importance within individual documents and the entire dataset. This results in a numerical feature matrix that captures the significance of words in context.

4. **Model Selection**
We've tested a few models:

1-Multinomial Naive Bayes
2-Gaussian Naive Bayes
3-Random Forest classifier

5. **Model Training**
We trained our chosen model using our cleaned data. The model learned from our data how to tell if a tweet is positive, negative, or neutral.

6.**Model Evaluation**
The final step involves assessing the performance of the sentiment analysis model. Common evaluation metrics include:

1-Accuracy: Measures the proportion of correctly classified posts.
2-Precision: Evaluates the accuracy of positive or negative predictions.
3-Recall: Assesses the model's ability to identify all positive or negative posts.
4-F1-Score: Balances precision and recall.


