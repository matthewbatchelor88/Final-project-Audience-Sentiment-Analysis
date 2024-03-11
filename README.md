# Audience Sentiment Analysis 
 
**Audience Sentiment Analysis**

This project serves as the culmination of a 9-week data analytics bootcamp with IronHack.

**Project Brief** 

 **Case Study 1 - Data Science End to End Project** 
 
 The goal is to build a predictive model in Python on top of a chosen business case. The project encompasses the entire data science 
 process, including:

* Data collection 
* Data cleaning and wrangling 
* Exploratory data analysis 
* Feature engineering 
* Preprocessing 
* Model selection and evaluation  
    Models to explore:
      * Random Forest, Naive Bayes, Neural Networks (utilizing Google Colab for computational reasons)
* Data visualization 

The project is structured as a complete pipeline that includes every step of the process.

**Source Data** 

(1) Tweet Data 
Can be accessed under tweet_emoitions.csv (also in this repo) 

* Inspiration: Point 15 in Interview Query: https://www.interviewquery.com/p/classification-projects
* Data source: Kaggle: https://www.kaggle.com/datasets/pashupatigupta/emotion-detection-from-text/data
  Includes 40,000 tweets, each tagged with an emotion

(2) Amazon Book Review Data
Can be accessed under tripadvisor_hotel_reviews.csv 

* Data source: https://www.kaggle.com/datasets/mohamedbakhet/amazon-books-reviews

**Problem Type**
This project addresses a multi-classification problem wherein the goal is to classify the emotion of a given text from a selection of emotions: positive, negative, neutral.

**Business Case** 

  **Mission**
  
Problem statement:
Companies receive more and more text-based feedback and fail to leverage that input to its maximum potential through effective prioritisation

Proposed solution:
My model will empower companies to unleash the potential of their customer-base through categorising customer feedback at scale

See 'Final Project Presentation' (PDF) for further detail

**Key Technologies**


* Machine Learning algorithms

Random Forest 
Naive Bayes 
Neural Networks

* Machine Learning techniques

KerasClassifier: A wrapper provided by scikeras.wrappers for integrating Keras models into scikit-learn pipelines
GridSearchCV: A technique for hyperparameter tuning, used to systematically search for the best parameters

* Python libraries
 
numpy: for numerical computing with arrays
pandas: for data manipulation and analysis
scikit-learn: for machine learning tasks such as model selection, metrics calculation, and data preprocessing
tensorflow: for building and training neural networks
joblib: for saving/loading models
pickle: for serializing Python objects

**Key documents in repository** 

* ipynb file of models
Models 1 - 3.1
TEST 1 and TEST 2 - Trained model tested on new data

* csv files
Referenced within ipynb Notebooks 

* PDF
Final Project Presentation - gives narrative of the project
