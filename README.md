# Password-Strength-Classifier
The passwords used in this analysis are from 000webhost leak that is available online.  The files contained the passwords with one more column i.e. their strength based on the commercial password strength meters. This dataset has been downloaded from Kaggle. 

First of all, I explored the complete dataset, how many passwords belong to each class. What are the effects of length on the strength of password. Since, this is a text data, and here the character type (number, alphabet, special characters) also make a difference in the strength of password, so we had to convert these passwords into subset of characters and thus, these will be acting as features. For this conversion, we have TFIDF vectorizer.

After this transformation, we had dataset in terms of only numerical values and password characters subsets in form of features. Next up, we splitted the data into test and train and trained model on this dataset. We got accuracy score of 1.0 which is though practically not possible and makes this an overgeneralized model. 

Lastly, we also tried our hands in predicting the strength of different passwords, and well the models perform pretty well.

So, here you go with this Password Strength Classifier.
