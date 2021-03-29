
[Final Paper.pdf](https://github.com/coreyyesavage/Text-Messaging-Classification/files/6184625/Final.Paper.pdf)
# Text-Messaging-Classification
Is the text spam or not?

## Technology
Python 3.7 

## Introduction
Since 2009, text message usage in the United States has increased exponentially to roughly two trillion texts per year. 
When comparing those numbers to phone calls and emails, the statistics become even more staggering. People in the United 
States send and receive five times as many text messages as they do phone calls [1]. Eighty-two percent of text messages 
are read within five minutes while only 1 out of 4 emails received are opened [1]. These numbers are very important, and 
they continue to trend towards more text message usage. Text messaging is no longer used for communication between friends 
and family only, it has also become common place for businesses and advertising. One inconvenient part of that advertising has
been the usage of text messaging for spam. Spamming is the use of a messaging system to send unsolicited messages to large 
numbers of recipients for the purpose of commercial advertising. With spam becoming so popular through text messaging, 
consumers need ways to filter out the spam.  This report is going to explain the analysis completed for the purpose of 
examining spam filtering through the use of machine learning algorithms. 

## Data Description
The dataset used in this analysis was taken from the website www.kaggle.com [2]. The data is compiled on Kaggle; however, 
it is gathered from the University of California, Irvine. The set contains 5,571 rows (instances) and 2 columns (attributes). 
The 2 columns are: text message and category (spam or ham). Spam texts are listed as spam while non-spam messages are listed 
as ham. Each instance represents a separate text message.

## Methodology
For this assignment, Python 3 was used. The 3 machine learning techniques, or methods, that were used in this analysis were: 
Multinomial Naïve Bayes, Logistical Regression, and Decision Trees. Within the Decision Trees method, random forest, 
extra randomized trees, and gradient boosting classifiers were also used. 

Multinomial Naïve Bayes is part of the sklearn package. This method is a classifier that is suitable for classification 
with discrete features, such as word counts [3]. With the text classification based off word counts within the entire 
text message, multinomial naïve bayes is a great technique to use.

Logistical Regression is part of the sklearn package as well. The Logistical Regression method uses a function to model a binary 
dependent variable. In this data set, the category column is a binary variable that is dependent on the text column input. 
This allows for logistical regression to be used on this particular dataset.

Like the previous techniques, Decision Trees are part of the sklearn package. Decision Trees are tree-like learning methods that make 
multiple observations and classifications. The goal is to create a model that predicts the value of a target variable by learning 
simple decision rules inferred from the data features. With this dataset, we are trying to do just that: predicting based off some
unknown patterns within the text message

## Results
![image](https://user-images.githubusercontent.com/60716763/112786282-e4188780-9023-11eb-9d86-d63f020e9c40.png)
![image](https://user-images.githubusercontent.com/60716763/112786142-956aed80-9023-11eb-85f3-d626f2f24a1b.png)
![image](https://user-images.githubusercontent.com/60716763/112786169-a61b6380-9023-11eb-865e-5f55244a4d43.png)

![image](https://user-images.githubusercontent.com/60716763/112786180-aca9db00-9023-11eb-916d-c0e7035656c5.png)
![image](https://user-images.githubusercontent.com/60716763/112786187-b29fbc00-9023-11eb-8169-d690b7578ab2.png)
![image](https://user-images.githubusercontent.com/60716763/112786202-b8959d00-9023-11eb-8415-87e7f332705b.png)

## Conclusion
The purpose of this analysis was to find a machine learning technique that could provide accurate results in
determining if a text message was spam or not (ham). This report makes it clear that multiple techniques allow for successful
classification of text messages. It can therefore be concluded that each analytical method and technique
utilized in this study, including Multinomial Naïve Bayes, Logistical Regression, and Decision Trees, are sufficient
and successful in determining if a text message is spam or ham. Consequently, this analysis found that multiple
machine learning techniques can be utilized properly and effectively for the purpose of filtering text messages for spam. 

## Resources
[1] A. Lemzy, "62 Text Messaging Statistics for Businesses - TextMagic", TextMagic, 2020. [Online]. 
Available: https://www.textmagic.com/blog/text-messaging-statistics-forbusinesses/?sscid=81k4_sj1t5. [Accessed: 23- Aug- 2020].

[2] "SMS Spam Collection Dataset", Kaggle.com, 2020. [Online].
Available: https://www.kaggle.com/uciml/sms-spam-collectiondataset. [Accessed: 23- Aug- 2020]

[3] ]"scikit-learn: machine learning in Python — scikit-learn 0.23.2 documentation", Scikit-learn.org, 2020. [Online]. 
Available: https://scikit-learn.org/stable/. [Accessed: 23- Aug- 2020]
