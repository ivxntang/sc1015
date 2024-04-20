# sc1015
email spam detection accuracy

## About

This is the mini project for sc1015 (introduction to data science and artificial intelligence)
Due to the widespread increase in the utilisation of online content, our team decided to focus on analysing spam email detection

## Problem definition
- are we able to spot fake emails analysing individual words alone?
- what are the textual similarities and differences between spam and ham emails?
- are we able to detect spam emails and classify it for users using machine learning models? If so, what are the telltale indicators?



## Dataset used 
### The dataset used for this project can be retrived [Here] (https://www.kaggle.com/datasets/mfaisalqureshi/spam-email)


## Presentation
### the video presentation can be found [Here]


## Brief process walkthrough

1. Data Preperation and Cleaning
   removal of irrelevant/empty column
2. Exploratory Data Analysis
   word cloud analysis
   email length analysis
   TF-IDF analysis
   
   








## Machine Learning
To convert text data to vectors for classification, we used Count vectorization and TF-IDF vectorization on text input data. Then, we trained the classification models on the train set and used the model on the test set to check for accuracy. Afterwards, we tried to combine multiple classification models in order to increase accuracy and robustness and create a versatile and reliable model.
### Models we used: Naive Bayes, Logistic Regression, Support Vector Machine, Random Forest, Neural Networks and Voting Classifier

## Contributions
### Ivan - Slides, code and script for 1. Problem Formulation, 2. Data Preparation and 3. Exploratory Data Analysis
### Wen Rong - Code, slides, video for 4. Machine Learning, video editor for Ivan’s part and overall video editor
### Napatr - Slides and video for 5. Data Driven Insights and 6. Evaluation, and recorded video for Ivan’s part

## References
### Gupta, S. (2023, July 13). Email spam filtering using naive Bayes classifier. Springboard Blog. https://www.springboard.com/blog/data-science/bayes-spam-filter/
### Shrivas, A. K., Dewangan, A. K., & Ghosh, S. M. (2021). Robust Text Classifier for Classification of Spam E-Mail Documents with Feature Selection Technique. Ingénierie Des Systèmes D’information (2001), 26(5), 437–444. https://doi.org/10.18280/isi.260502
