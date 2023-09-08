# Bengali-Hate-Speech-Motivation-Classification

This project aims to predict the motivation behind hate speech texts in the Bengali langauge. I used the following combinations from scikit-learn to create 4 machine learning models in total:

* CountVectorizer + MultinomialNB
* TFIDF Vectorizer + Multinomial NB

* CountVectorizer + LogisticRegression
* TFIDFVectorizer + LogisticRegression

I wanted to compare the models' metrics to look at the differences in how they handled this particular dataset. After conducting the metric evaluations, I then retrieved the most informative features for each class in each model.

### The Data
For the data used in this project, I downloaded it from this url (https://archive.ics.uci.edu/dataset/719/bengali+hate+speech+detection+dataset). The data was split into 3 csv files (test.csv, train.csv, and validate.csv) with two columns: "text" and "label", the first representing the sample of hate-speech text and the other corresponding to the motivation behind the comment. There are five categories of the motivation/label column: "Personal", "Political", "Religious", "Neutral" and "Geopolitical". The full citation for the data is below. 

### Citation
Md. Rezaul Karim, Bharathi Raja Chakravarti, John P. McCrae, and Michael Cochez, “Classification Benchmarks for Under-resourced Bengali Language based on Multichannel Convolutional-LSTM Network”, Proc. of IEEE International Conference on Data Science and Advanced Analytics (DSAA’2020), Sydney, Australia, October 2020.