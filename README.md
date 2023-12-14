## Project Overview
• Created a machine learning model that **detects/classifies a SMS into SPAM or HAM (normal) based on the textual data using Natural Language Processing.**<br/>
• **Engineered features like word_count, contains_currency_symbol, and contains_number** from the text SMS.

## How will this project help?
• This project **helps in filtering/cleaning the SMS from the phone.**

## Resources Used
• Packages: **pandas, numpy, sklearn, matplotlib, seaborn, nltk.**<br/>
• Dataset by **UCI Machine Learing on Kaggle**: https://www.kaggle.com/uciml/sms-spam-collection-dataset

## Exploratory Data Analysis (EDA)
• **Exploring NaN values** in dataset<br/>
• **Plotted countplot** for SMS labels Spam vs. Ham

## Feature Engineering
• Handling imbalanced dataset using Oversampling

![image](https://github.com/Siddhartha082/NLP_SPAM_SMS_Classification/assets/110781138/aa392f86-ff8e-406e-bb29-322fbda136f7)

![image](https://github.com/Siddhartha082/NLP_SPAM_SMS_Classification/assets/110781138/11076a59-3a5b-4f14-a208-4d2d2a3c52ec)

![image](https://github.com/Siddhartha082/NLP_SPAM_SMS_Classification/assets/110781138/bd16a3a8-b267-4e7c-82f6-6fa8f7ed9c4f)


## Data Cleaning
• Removing special character and numbers using regular expression<br/>
• Converting the entire sms into lower case<br/>
• Tokenizing the sms by words<br/>
• Removing the stop words<br/>
• Lemmatizing the words<br/>
• Joining the lemmatized words<br/>
• Building a corpus of messages

## Model Building and Evaluation
**Metric: F1-Score**<br/>
• Multinomial Naive Bayes: 0.943<br/>
• Decision Tree: 0.98<br/>
• **Random Forest: 0.994**<br/>
• Voting (Decision Tree + Multinomial Naive Bayes): 0.98


![image](https://github.com/Siddhartha082/NLP_SPAM_SMS_Classification/assets/110781138/9bf1b72f-f426-4c0c-aefe-6fe734eaf993)


_**Note: Evaluation scores are obtained using cross validation.**_

## Model Prediction

![image](https://github.com/Siddhartha082/NLP_SPAM_SMS_Classification/assets/110781138/779ce363-b361-4ac7-8da0-06743ff2132a)

