This project focuses on classifying SMS messages as either "ham" (legitimate) or "spam" using a Logistic Regression model with TF-IDF (Term Frequency-Inverse Document Frequency) Vectorizer for feature extraction. The objective is to develop a reliable and efficient classifier that accurately filters spam messages from legitimate ones.

Data Preprocessing: Includes handling missing data, cleaning the SMS text by removing punctuation, stopwords, and special characters. The text is then tokenized, and the TF-IDF Vectorizer is applied to convert the raw text data into numerical features that reflect the importance of each word in the corpus while down-weighting common but less informative words.

Model Training: A Logistic Regression model is trained on the features generated by the TF-IDF Vectorizer. Logistic Regression is chosen for its simplicity, efficiency, and interpretability in binary classification tasks. It predicts the probability of a message being spam based on the learned relationships between word importance and the labels.

Dataset Link :https://github.com/sakethlingerker/SMS-classifier/blob/main/sms_data.csv
