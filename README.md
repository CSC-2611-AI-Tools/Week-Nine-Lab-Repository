
# Week-Nine-Lab-Repository
This is repository dedicated to storing code that has been taken from lab nine, which can be meant for future reference

## Lab 9: KNN Classification with Text Data and Census Data Analysis
For Part 1 of this lab, you are not allowed to use any built-in KNN functions or built-in functions to generate a TF-IDF matrix. 
You must complete the KNN and TF-IDF parts from scratch. If you choose not to code KNN and TF-IDF from scratch, you will receive 0 points for 
questions 2 and 5 in Part 1, but you can still earn points for the other questions.

### Part 1
K-Nearest-Neighbor (KNN) classification on Newsgroups. For part 1 of this lab, you will use a subset of the 20 Newsgroup data set. 
The full data set contains 20,000 newsgroup documents, partitioned (nearly) evenly across 20 different newsgroups and has been often 
used for experiments in text applications of machine learning techniques, such as text classification and text clustering 
The assignment data set contains a subset of 1000 documents and a vocabulary of 5,500 terms. Each document belongs to one of two 
classes Hockey (class label 1) and Microsoft Windows (class label 0). The data has already been split (80%, 20%) into training and test data. 
The class labels for the training and test data are also provided in separate files. The training and test data are on term x document format, 
containing a row for each term in the vocabulary and a column for each document. The values in the table represent raw term occurrence counts. 
The data has already been preprocessed to extract tokens, remove stop words, and perform stemming (so, the terms in the vocabulary are stems 
not full terms). Please be sure to read the readme.txt file in the distribution.

### Part 2
For this problem you will use a simplified version of the Adult Census Data Set. In the subset provided here, some of the attributes have been 
removed and some preprocessing has been performed
