
# Predicting-Employee-Attrition

This project aims to predict employee attrition using the Logistic Regression algorithm from the scikit-learn library. The dataset used for this project is the IBM HR Analytics Employee Attrition & Performance dataset.




## Dependencies

Dependencies

Python 3.x

pandas

numpy

scikit-learn

Steps



## Process

1.Load the dataset: Load the IBM HR Analytics Employee Attrition & Performance dataset into a pandas DataFrame. Ensure the dataset is in a suitable format for analysis.

2.Preprocess the dataset: Handle missing values by dropping them, encode categorical variables using LabelEncoder, and scale numerical features using StandardScaler to prepare the dataset for modeling.

3.Split the dataset into training and testing sets: Split the preprocessed dataset into training and testing sets using train_test_split to evaluate the model's performance. Ensure the test size is suitable for the dataset.

4.Train the Logistic Regression model on the training set: Train a Logistic Regression model on the training set to learn the patterns and relationships between the features and the target variable. Ensure the model is configured correctly.

5.Evaluate the model on the testing set: Evaluate the trained model on the testing set to measure its performance using metrics such as accuracy, precision, recall, and F1-score. Analyze the results to identify areas for improvement.

6.Optimize the model using GridSearchCV: Perform hyperparameter tuning using GridSearchCV to optimize the model's performance. Define a range of hyperparameters to search and evaluate the model's performance using a suitable scoring metric.
