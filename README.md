# Fall_Quarter_Data_Project_Project_2023
Upload R coding for Kaggle Titanic Survival Competition

This Kaggle competition provides users with a Titanic database of passengers who survived or passed away during their travel along with demographics and ticketing information of the passengers. The goal is to predict the status of a passenger's survival utilizing the training dataset.

# Steps
- Imputed the 'NA' values found in our training dataset with the mice package in R
- Utilized randomForest() to determine which predictors were essential to creating our model
- Imputed 'NA' values in testing dataset with the mice package again
- Created a logistic regression model to predict the passengers' survival since we have binary answer

# Result:
- 77.3% Accuracy Score from Kaggle
