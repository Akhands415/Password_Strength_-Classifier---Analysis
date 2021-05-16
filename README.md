# Password_Strength_Classifier - Analysis

Predict Password Strength using Natural Language Processing

# A Machine Learning model that predicts whether the password is strong or not.

Datset Link: https://www.kaggle.com/bhavikbb/password-strength-classifier-dataset

The passwords used in our analysis are from 000webhost leak that is available online. How did we figure out which passwords were stronger and which were weaker? Well, there is a tool called PARS by Georgia Tech university which have all the commercial password meters integrated into it. All I did was give that tool all the passwords and it gave me new files for each commercial password strength meter.

# Content 

1. Exploring Data 
2. code to check all the missing values in my dataset
3. shuffling randomly for robustness
4. create a custom function to split input into characters of list
5. import TF-IDF vectorizer to convert String data into numerical data
6. Apply Logistic on data as use-case is Classification
7. Doing prediction for specific custom data
8. check Accuracy of model 
9. create report of model
10. Feature Engineering
