# Creditccardml
It contains a  ml project  regarding credit card approval based  on economic and financial conditions
-- Challenges faced in this project:
a)There were lot of null values
b) Some of the features also had outliers
c) There were lot of skewed data present in the features

-- Steps taken to overcome challenges:
a) Removed the rows containing outliers with help of IQR method
b) The null values were filled with either the mode of categorical features  or filled with 0 in numerical features
c) Skewed data was treated with the help of log transformation as values were right skewed

-- Overview of the project:
a)EDA was done to get general understanding of data
b)Data cleaning was done to remove ouliers and null values were filled 
c) Data transformation was done to treat the skewed data
d) ML models were applied to classify whether the credit card can be approved or not:
ML algorithms applied after being splitted for training and testing:
1) Logistic Regression
2) KNN
3) Decision Tree
4) Support Vector Machine

#Conclusion of the project:
All the ML Algorithms were giving output of about 88-89 percent which signified that the ML model is built properly with proper testing and training.
