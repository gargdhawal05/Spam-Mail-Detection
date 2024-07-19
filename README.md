# Spam Mail Detection Project

## Project Overview

This project aims to build a Spam Mail Detection system using Machine Learning models. The dataset used for this project consists of 5572 mails categorized as 'spam' or 'ham' (not spam), which is sourced from Kaggle. The project evaluates multiple machine learning models to determine which one performs the best in classifying emails correctly.

## Dataset

The dataset contains 5572 emails labeled as either 'spam' or 'ham'. It can be found on Kaggle and includes two columns:
- **Category**: The label of the email, either 'spam' or 'ham'.
- **Message**: The content of the email.

## Machine Learning Models

We have used the following machine learning models to classify the emails:
- Logistic Regression
- Support Vector Machine (SVM)
- Random Forest
- Naive Bayes

The accuracy of each model is calculated and compared to determine the best performing model.

## Project Components

### Data Preprocessing

- **Text Cleaning**: Removal of stop words, punctuation, and conversion to lowercase.
- **Feature Extraction**: Using `TfidfVectorizer` to convert the email text into numerical features suitable for machine learning models.

### Model Training and Evaluation

- **Train-Test Split**: The dataset is split into training and testing sets.
- **Model Training**: Each machine learning model is trained using the training set.
- **Model Evaluation**: The models are evaluated on the testing set, and their accuracy is compared. A confusion matrix is created for each model to visualize the performance.

### Visualization

- **Word Cloud**: A word cloud visualization is created for both 'spam' and 'ham' emails. The size of each word in the word cloud is proportional to the number of occurrences of that word in the respective category of emails.

## Conclusion

In this project, we have successfully built and evaluated multiple machine learning models to detect spam emails. The performance of each model was compared using accuracy and confusion matrices. Additionally, word cloud visualizations provided insights into the most common words in spam and ham emails. The code and methods demonstrated here can be further expanded and improved for more robust spam detection systems.
