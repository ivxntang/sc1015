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
### The dataset used for this project can be retrived [Here](https://www.kaggle.com/datasets/mfaisalqureshi/spam-email)


## Presentation
### the video presentation slides can be found in "sc1015 slides.pdf"


## Brief process walkthrough

1. Data Preperation and Cleaning
   + removal of irrelevant/empty column
2. Exploratory Data Analysis
   + word cloud analysis
   + email length analysis
   + TF-IDF analysis
3. Machine Learning
4. Data-Driven Insights and Recommendations
   + Key details
   + Count Vectorization outperforms TF-IDF
   + Implementing a Combination of Classifiers with Soft Voting    
   




## Machine Learning
To convert text data to vectors for classification, we used Count vectorization and TF-IDF vectorization on text input data. Then, we trained the classification models on the train set and used the model on the test set to check for accuracy. Afterwards, we tried to combine multiple classification models in order to increase accuracy and robustness and create a versatile and reliable model.
### Models we used: Naive Bayes, Logistic Regression, Support Vector Machine, Random Forest, Neural Networks and Voting Classifier

## Data-Driven Insights and Recommendations
We compared the test classification accuracy of each classification model and found some key details: SVM showed the highest Accuracy for both count vectorization and TF-IDF,  Naive Bayes Classifier and Logistic Regression performed poorly with TF-IDF in email spam classification. We also found that Count Vectorization in general performed better compared to TF-IDF, possibly due to a smaller data sample. 

We recommend using the combination of all classifiers specified (excluding Naive Bayes and Logistic Regression with TF-IDF due to poor accuracy) with Soft Voting as it yielded the highest classification accuracy for email spam classification compared to other classifiers. 

## Contributions
### Ivan - Slides, code and script for 1. Problem Formulation, 2. Data Preparation and 3. Exploratory Data Analysis
### Wen Rong - Code, slides, video for 4. Machine Learning, video editor for Ivan’s part and overall video editor
### Napatr - Slides and video for 5. Data Driven Insights and 6. Evaluation, and recorded video for Ivan’s part

## References
### Gupta, S. (2023, July 13). Email spam filtering using naive Bayes classifier. Springboard Blog. https://www.springboard.com/blog/data-science/bayes-spam-filter/
### Sanjay, M. (2020, Jan 14) Model Performance boosting with Voting-Classifier. https://medium.com/analytics-vidhya/performance-boosting-with-voting-classifier-ea69313a367c
### Shrivas, A. K., Dewangan, A. K., & Ghosh, S. M. (2021). Robust Text Classifier for Classification of Spam E-Mail Documents with Feature Selection Technique. Ingénierie Des Systèmes D’information (2001), 26(5), 437–444. https://doi.org/10.18280/isi.260502
### Kaplan, S. (2024, Feb 22) Machine Learning 101: CountVectorizer vs TFIDFVectorizer. https://enjoymachinelearning.com/blog/countvectorizer-vs-tfidfvectorizer/

