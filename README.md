

Email Spam Prediction using Logistic Regression

Overview

This project focuses on detecting whether an email is spam or ham (non-spam) using machine learning techniques. A Logistic Regression model is used for the classification task, where emails are first transformed into feature vectors using TF-IDF (Term Frequency-Inverse Document Frequency) before feeding them into the model.

Dataset

The dataset, stored in mail_data.csv, contains two columns:

Category: The class label of the email (spam or ham).
Message: The content of the email.

Label Encoding:
Spam emails are labeled as 0.
Ham emails are labeled as 1.

Project Workflow

1. Data Loading & Preprocessing:
Load the dataset into a Pandas DataFrame.
Handle missing values by replacing them with empty strings.
Encode the labels where spam is 0 and ham is 1.

2. Feature Extraction:
Use TfidfVectorizer from scikit-learn to convert email texts into numerical feature vectors.
Split the dataset into training and testing sets (80% training, 20% testing).

3. Model Training:
Train a Logistic Regression model on the training data.

4. Model Evaluation:
Evaluate the accuracy on both training and test sets.
Use accuracy as a metric to evaluate the model's performance.

5. Prediction:
Make predictions on new email messages to classify them as either spam or ham.

Dependencies
Make sure you have the following Python libraries installed:

numpy
pandas
scikit-learn

Results
The model achieves an accuracy of:
Training Accuracy: ~96.77%
Testing Accuracy: ~96.68%

This shows that the model is performing well on unseen data and can effectively classify spam and ham emails.








Email Spam Prediction Using Logistic Regression 📧📊


Overview:
         This project focuses on email classification to detect whether an email is spam or ham (non-spam) using a Logistic Regression model. The emails are transformed into numerical feature vectors using TF-IDF (Term Frequency-Inverse Document Frequency), ensuring effective feature extraction before classification.

Dataset 📂

The dataset (mail_data.csv) comprises two columns:

Category: Class label of the email (spam or ham).
Message: Content of the email.

Label Encoding:

Spam emails: 0
Ham emails: 1


Project Workflow 🛠️

1. Data Loading & Preprocessing 📥

Load the dataset into a Pandas DataFrame.

Handle missing values by replacing them with empty strings.
Encode the labels: Spam (0) and Ham (1).

2. Feature Extraction ✍️

Use TfidfVectorizer from scikit-learn to transform email texts into numerical feature vectors.

Split the dataset into training (80%) and testing (20%) sets.

3. Model Training 🤖
Train a Logistic Regression model on the training data to classify emails.

4. Model Evaluation 📈

Evaluate the model's accuracy on both the training and testing datasets.
Use accuracy as the primary metric to assess model performance.

5. Prediction 🔍

Predict new email messages to classify them as either spam or ham.

Dependencies 🛒

Ensure you have the following Python libraries installed:

numpy
pandas
scikit-learn


Results ✅
The Logistic Regression model achieves:


Training Accuracy: 96.77%

Testing Accuracy: 96.68%


This indicates robust performance on unseen data, effectively distinguishing spam emails from legitimate ones.
