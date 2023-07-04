# Creditworthiness Prediction
# Project Overview 

Banks are often posed with a problem to whether or nor a client is credit worthy. They commonly
employ data mining techniques to classify a customer into risk categories such as category A (highest rating)
or category C (lowest rating).
In this project, we will use machine learning models and compare their accuracy in assessing the client's credit.

# Installation and Setup
# Codes and Resources Used
- Editor Used: Google Colab
- Language: R

# Package used 
- Data Manipulation:
dplyr
- Data Visualization:
rpart.plot
e1071
- Machine Learning:
tree, rpart, randomForest, caret, caTools, naivebayes, nnet


# Data
- A bank collects data from past credit assessments. The file "creditworthiness.csv" contain data on 2500 customers, of which the credit rating for 1962 of them has been assessed as either A, B, or C, coded as 1, 2, or 3, respectively, with the remaining 538 needing to be classified.
Each assessment lists 46 attributes of a customer. The last attributes “credit rating" is the result of the assessment.
- The dataset is splitted into 50% training set and 50% test set and only include the data with known ratings.

