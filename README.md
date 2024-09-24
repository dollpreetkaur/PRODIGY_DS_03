# PRODIGY_DS_03

### Customer Purchase Prediction Using Decision Tree Classifier
This repository contains a project aimed at building a Decision Tree Classifier to predict whether a customer will purchase a product or service based on their
demographic and behavioral data. The Bank Marketing dataset from the UCI Machine Learning Repository has been used to train and evaluate the model.
### Project Overview:
The goal of this project is to build a predictive model using a Decision Tree Classifier that can determine whether a customer will subscribe to a bank product (e.g., term deposit) based on various demographic and behavioral factors.

Key steps involved in the project include:
Data Preprocessing: Handling missing data, encoding categorical features, and splitting data into training and testing sets.
Model Building: Training a Decision Tree Classifier.
Hyperparameter Tuning: Optimizing the model using techniques such as GridSearchCV.
Model Evaluation: Using metrics such as accuracy, confusion matrix, and classification report to assess the model performance.

### Dataset
The dataset used for this project is the Bank Marketing dataset from the UCI Machine Learning Repository. The dataset contains 41,188 records and 21 attributes, including:

Customer demographics: Age, job, marital status, education.
Customer behavior: Whether the customer has a housing loan, personal loan, etc.
Previous contact information: Contact type, last contact day, and duration.
Target variable: Whether the customer has subscribed to the product ('yes' or 'no').
You can download the dataset from the UCI Machine Learning Repository: Bank Marketing Dataset
https://archive.ics.uci.edu/dataset/222/bank+marketing

### Requirements
Ensure you have the following Python packages installed:
numpy
pandas
scikit-learn
matplotlib
seaborn

### Data Preprocessing
The dataset requires preprocessing to handle categorical variables, missing values, and feature scaling. Key steps include:

Encoding categorical variables: Using techniques like one-hot encoding or label encoding for categorical columns (e.g., job, marital status, education).
Splitting the data: Dividing the dataset into training and test sets for model evaluation.

### Model Building
The project utilizes a Decision Tree Classifier to build the model. A basic decision tree is trained using the training set.

### Hyperparameter Tuning
To improve model performance, we use GridSearchCV to tune hyperparameters such as the depth of the tree and the criterion used for splits.
### Model Evaluation
To evaluate the model’s performance, we calculate the accuracy, confusion matrix, and classification report on the test set

### Insights
After training and evaluating the model, we can draw several insights, such as:

Top predictors: Identifying the most influential features in predicting whether a customer will subscribe.
Model performance: Understanding the accuracy and potential improvements through hyperparameter tuning.

