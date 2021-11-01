# Emotion-Recognition-for-Counselling
## Problem Statement : 
Emotion Recognition For Counselling
* Our model detects emotion types from health-related posts and show how high-level and abstract features can be employed to detect emotions 	
* Text data is taken as input from the user and is used it to analyse the emotions based on the text input by the user . In the initial stage of the model we keep it simple to analyse two emotions i.e. stress and not stress based on our dataset .
## Objective
* To build a emotion recognition system for counselling.
## System/Software Architecture

## Dataset : Dreaddit dataset
* The dataset Dreaddit is a new text corpus of lengthy multi-domain social media data for the identification of various emotions. The dataset consists of 190K posts from five different categories of Reddit communities .
* We use the ‘Text’ and ‘Label’ column for our model .
## Example from dataset

## Training and Test Set 
* This results in a total of 2,838 train data points and 715 test data points which can be used for training and testing the model. 
## Techniques Used
* Text Preprocessing
         1. Taking text in range of a-z or A-Z 
         2. Lowering the words 
         3. Stopwords Removal
         4. Lemmatization
         5. Stemming 
* Creating Bag of Words
* Training the Model – Applied various classification algorithms like SVM , Naïve Bayes , Random Forest , Logistic Regression , K-NN , Decision Tree
* Tuning the Hyperparameters
## Result Analysis
* The Best Accuracy of 74% is given by the Logistic Regression Model .
* We will use model trained with Logistic Regression algorithm for prediction of emotions from the input text data.




