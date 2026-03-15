# ML-Basics-Optimization
Machine Learning baseline model project demonstrating data preprocessing, model training, evaluation using accuracy and F1 score, cross-validation, and hyperparameter tuning using Python and Scikit-learn.
Titanic Survival Prediction (Machine Learning)

This project demonstrates building and improving a baseline machine learning classification model using the Titanic dataset. The goal is to predict whether a passenger survived based on passenger attributes.

Objective

The objective of this project is to:

Build a baseline machine learning model

Apply data preprocessing
Use feature scaling
Perform hyperparameter tuning
Evaluate the model using multiple metrics

Dataset
The project uses the Titanic dataset, which contains passenger details such as:
Passenger Class (Pclass)
Sex
Age
Siblings/Spouses aboard (SibSp)
Parents/Children aboard (Parch)
Fare
Embarked

Target Variable:
Survived (0 = Did not survive, 1 = Survived)

Project Workflow
1. Data Preprocessing

Handled missing values
Filled missing Age values with the median

Filled missing Embarked values with the most frequent value
Converted categorical variables using One-Hot Encoding

2. Train-Test Split
The dataset was split into training and testing sets to evaluate model performance.

3. Baseline Model
A Logistic Regression model was used as the baseline model.

4. Feature Scaling
StandardScaler was applied to scale numerical features.

5. Hyperparameter Tuning
GridSearchCV was used to optimize Logistic Regression parameters.

6. Model Evaluation
The model was evaluated using:
Accuracy
F1 Score

Confusion Matrix

Model Performance
Baseline Model
Metric	Score
Accuracy	0.8100
F1 Score	0.7639
Scaled Model
Metric	Score
Accuracy	0.8100
F1 Score	0.7639
Hyperparameter Tuned Model
Metric	Score
Accuracy	0.7821
F1 Score	0.7299
Confusion Matrix

A confusion matrix was used to compare predicted and actual classifications to better understand model performance.

Technologies Used
Python
Pandas
NumPy
Scikit-learn
Jupyter Notebook


Conclusion
The baseline Logistic Regression model achieved the best performance with an accuracy of 81% and an F1 score of 0.76. Feature scaling produced similar results, while hyperparameter tuning slightly reduced the performance on the test set.
