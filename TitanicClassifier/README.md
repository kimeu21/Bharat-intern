# TitanicClassificationIA23
This is a repository for my classification solution for the titanic problem from Kaggle. The repository contains every file needed for execute my solution in Google Colab.



Challenges Faced:

Missing Values: I encountered missing values in the Age, Cabin, and Embarked columns.
Outliers: During our exploration, I detected several outliers in columns such as Age, SibSp, Parch, and Fare.
Data Categorization: Some columns, like Sex and Embarked, were categorical and needed to be transformed to be utilized in predictive models.
Model selection

Implemented Solutions:

Handling Missing Values: I imputed missing values in Age using median value. For Cabin, given the high amount of missing values, I considered either dropping it or extracting relevant information from it. For Embarked, I replaced missing values with the most common port.
Outlier Management: I employed statistical methods to identify and handle outliers, ensuring they did not skew my model.
Categorical Data Transformation: I transformed categorical columns into numeric values using encoding techniques, like one-hot encoding, so they could be utilized in our models.


SVC Kagle result: 0.78229
COLAB
https://colab.research.google.com/drive/1RB4zQy-8G05bwDkQcF8O46IElsJO3gJS?usp=sharing
