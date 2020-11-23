# Building-Spam-Classifier
Building a classifier to classify ham and spam emails.
### Business Problem:
Effective Communication is plays major role in any business.E-mail is one of the most widely used communication tool. One problem with email communication is reception of spam emails,that are of no use or sometimes harmful to system. Getting rid of spam emails helps in effective business communication and saves lot of time. Manual handling of such emails consumes time and manpower. In this project a classifier that classifies spam and ham(non-spam) is built using machine learning techniques and algorithms.
### Machine Learning Problem:
To filter out spam emails from incoming emails a classifier is needed. Here this problem is posed into a binary classification problem, that classifies datapoints into two classes,spam or ham(not spam).

### The Dataset:
Here we will introduce the dataset we will be using for this project. The dataset used in this project is from Apache SpamAssassin.
Apache SpamAssassin is the #1 Open Source anti-spam platform giving system administrators a filter to classify email and block spam (unsolicited bulk email). It uses a robust scoring framework and plug-ins to integrate a wide range of advanced heuristic and statistical analysis tests on email headers and body text including text analysis, Bayesian filtering, DNS blocklists, and collaborative filtering databases.

Apache SpamAssassin is a project of the Apache Software Foundation (ASF). You can find more about them from the below link: https://spamassassin.apache.org/
The dataset we will be using is hosted at the below link: http://spamassassin.apache.org/old/publiccorpus/
The dataset contains two folders namely 'easy_ham' & 'spam' containing examples of ham emails(non-spam) & spam emails.a

### Evaluation metric:
Here our requirement is to filter out spam emails and get ham emails. it is crucial that we should not miss any important email (ham) by misclassifying it as spam. So we need a high precision model rather than high recall. High precision ensures that whichever model is classified as spam will most probably be spam actually. 
precision=true positives/(true positives+false positives)

#### Credits & References: 
This project is done under the guidance of Mr.Rajtilak Bhattacharjee,Machine Learning Engineer @ CloudxLab.com.
Profile link:https://cloudxlab.com/p/rajtilak-bhattacharjee-9vrdrq1j/ 
