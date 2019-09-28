# hack-srm
predicting cyber bullying on twitter  
Goal: Using Python to detect cyber-bullying on Twitter based on categories and kinds of language used with at-risk tweets

Data source:
Twitter API

Main libraries used:
Python-Twitter, NLTK, Pandas

Bullying (binary classification based on cross-validation of 5 members):

1 = Bullying 0 = Non-Bullying

Categories/types of bullying used to retrieve and evaluated with tweets (labels not included in published csv of dataset):
Based on past literature and research regarding cyberbullying detection, keyword search of

Physical Appearance

Sexuality

Race

Culture

Political-oriented

Intelligence

Curse Words

"Mean Words" (idiot, loser etc.)

Models evaluated with n-grams (unigram, bigrams, trigrams, combination (n=3):
Naive Bayes, Decision Tree, Logistic Regression, Support Vector Machine
