# Text-Classification-

Project Description : This project consists of two Datasets - mini_newsgroups and 20_newsgroups. Both the datasets consists of                       20 different news groups and we need to predict that  the given test file belongs to which category of                         news group. I have implemented this using the inbuilt Multinomial Naive Bayes(in sklearn) as well as I                         have made my own Naive Bayes Classifier from scratch without using inbuilt library.

Dataset link : http://archive.ics.uci.edu/ml/datasets/Twenty+Newsgroups

Project Overview :
1. All the text files are cleaned by removing some of the headers , removing the stop words , removing the punctuations ,        removing the digits and then a dictionary of all the words as the key and their frequencies as the value is created.
2. Then this dictionary is sorted in decreasing order and top K(here 4000) frequency words are chosen to be the features of      our training as well as testing dataframe.
3. Finally we create the fit function and the predict function for implementing Naive Bayes. 
4. An accuracy of 75-80% is achieved in case of 20_newsgroups and 65-70% in case of mini_newsgroups by both self                  implementation and inbuilt Multinomial Naive Bayes.  

