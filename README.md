# classification-challenge

## Module 13 Challenge

In this challenge, I compared the performance of two machine learning models, Logistic Regression and Random Forest Classifier, in predicting spam emails. The dataset used was sourced from the UCI Machine Learning Library and contained various features extracted from emails, with the target variable indicating whether an email is spam or not.


## The workflow of the project can be summarized as follows:

Data Retrieval and Exploration: 

I imported the dataset using Pandas and explored its structure by displaying the first few rows. I also checked the balance of the target variable to ensure there was no significant class imbalance.

Data Preprocessing: 

I split the dataset into features (X) and labels (y) and further split the data into training and testing sets using the train_test_split function from scikit-learn. I also scaled the features using StandardScaler to ensure uniformity in feature scales.


## Model Building and Evaluation:

Logistic Regression: 

I trained a logistic regression model on the scaled training data and evaluated its performance by calculating the accuracy score on the testing data.

Random Forest Classifier: 

I trained a Random Forest Classifier model on the scaled training data and evaluated its performance using the accuracy score on the testing data.

Results and Conclusion: 

I compared the performance of both models based on their accuracy scores. The Random Forest Classifier outperformed the Logistic Regression model, achieving a higher accuracy score on the testing data.

In conclusion, the Random Forest Classifier is better at predicting spam emails compared to Logistic Regression in this instance. The results suggest that Random Forest is more suitable for handling complex datasets with non-linear relationships.


## Acknowlegements:

I extend my gratitude to academic instruction, DataCamp, and the Stack Overflow community for their invaluable contributions to this project. Academic instruction provided the foundational knowledge and guidance essential for tackling data analysis challenges, while DataCamp's interactive courses and hands-on exercises significantly enhanced my skills and techniques. Moreover, the Stack Overflow community's wealth of discussions and solutions offered insights, problem-solving approaches, and best practices crucial for overcoming obstacles encountered during development. Together, these sources have played a pivotal role in shaping my understanding and proficiency in data analysis, for which I am sincerely thankful.