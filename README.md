# How-Personal-Perceptions-of-COVID-19-Have-Changed-Over-Time
 **Abstract:**

In this work, we used datasets on emotional responses and comments to COVID-19 to analyze people’s perceptions towards COVID-19. Based on the trend of perceptions, we predicted the trend for the next month.

**Data:**

[Ground Truth](https://arxiv.org/abs/2004.04225): used for training the sentiment classification models.

[Dataset used for prediction from January 1st to April 17th](https://www.kaggle.com/tianysun/covidtext): used for topic extraction and prediction.

**Models:**
* Models used for sentiment classification:

Model Name | Accuracy |
------------ | -------------
Naive Bayes  | 0.8440
Logistic Regression | 0.9528
Random Forests | 0.7337
BERT | 0.8538
XLNet | 0.6547
Liear SVM | 0.7989
Linear SVC | 0.9218
LSTM | 0.9534
RoBERTa | 0.7410
DistilBERT | 0.8987

* Model used for topics extraction:  

LDA 

* Models used for sequential prediction: 

Model Name | RMSE (Sentiment) | RMSE (Topic)
------------ | ------------- | -------------
LSTMLB | 64.56 | 125.73
LSTMWM | 56.71 | 170.96
LSTMTS | 67.62 | 159.57
LSTMM | 277.72 | 242.68
ARIMA | 27.07 | 85.71


**Details:**

[Slides](https://github.com/TianyiSun00234/How-Personal-Perceptions-of-COVID-19-Have-Changed-Over-Time/blob/main/Slides.pdf)

[Paper](https://github.com/TianyiSun00234/How-Personal-Perceptions-of-COVID-19-Have-Changed-Over-Time/blob/main/How%20Personal%20Perceptions%20of%20COVID-19%20Have%20Changed%20Over%20Time.pdf)

