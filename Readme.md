# Spam Classifier

Multinomial Naive-Bayes is used for classifying whether a sms message is spam or not. Multinomial Naive Bayes is suitable for classification with discrete features. The model takes in integer word counts as its input. 

Data is cleaned by converting all strings to their lower case form, removing the punctuation and by using Stop Words parameter. Also, I have used Bag of Words approach to extract features from the text data for the eventual classification by the ML model. Under this process, I have converted a collection of documents to a matrix, with each document being a row and each word(token) being the column, and the corresponding (row,column) values being the frequency of occurrence of each word or token in that document.

The data set is a large collection of text data (5,572 rows of data): [Dataset used](https://drive.google.com/file/d/1wzac8eww8yzbOkNB9AXRzUbLtL9-unvC/view?usp=sharing)