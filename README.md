# AUTOMATIC-SARCASM-DETECTION

## Problem Description
Recently, much attention is being paid to the identification of sarcastic posts on social media, particularly because sarcastic comments in the form of tweets frequently contain positive words that reflect negative or undesirable features. More important now than ever is indeed the need of a device that can recognize sarcasm automatically and effectively. This paper presents a Machine Learning Approach for the detection of sarcasm sentences in news websites. The above described task was treated as a binary classification problem
and a series of ML classifiers were chosen as candidate models. Performances of the latter were successively analyzed and compared using accuracy scores and F1-measures.

## Word clouds

SARCASTIC HEADLINES        | NON-SARCASTIC HEADLINES
:-------------------------:|:-------------------------:
![](https://user-images.githubusercontent.com/57104110/136662974-3570dc52-722a-4db7-b1d5-0f6b48762c8b.png) | ![](https://user-images.githubusercontent.com/57104110/136662980-1afa1654-7061-42c8-b644-07aef8fb2629.png)

## Model(s) selection

The idea in this project was to treat the problem as any other standard classification problem. In particular, as we have a labeled training dataset, the aim was to build supervised classification models to classify the data into two different classes which are sarcastic and non-sarcastic. The chosen approach was the Machine Learning-based one and the models to build are:

* Logistic Regression
* Decision Tree
* Naive Bayes
* Random Forest
* Support Vector Machine

## Results
The table below shows the best results in terms of train accuracy and test accuracy obtained by each of the models:

![alt text](https://user-images.githubusercontent.com/57104110/136663223-c8a5746c-1406-4eed-af1e-b6c2b4a44a8d.png)


