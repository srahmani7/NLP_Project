# Natural Language Processing (NLP)


<p align="center">
<img src="https://github.com/soheil-ra/NLP/blob/main/Images/image2.png?raw=true" />   
</p>

## **Table of Content**<br>

ReadMe contains the following sections:

**1. Overview -** [Overview](https://github.com/soheil-ra/NLP#Overview)<br>
**2. Goals -** [Goal](https://github.com/soheil-ra/NLP#Goals)<br>
**3. Motivation & Background -** [Motivation & Background](https://github.com/soheil-ra/NLP#Motivation-and-Background)<br>
**4. Data -** [Data](https://github.com/soheil-ra/NLP#Data)<br>

This assignment contains the following areas:

**5. Dataset -** [Dataset](https://www.kaggle.com/aswin0821/amazon-reviews) <br>
**6. Code -** [Code]()<br>
**7. Images -** [Images](https://github.com/soheil-ra/NLP/tree/main/Images)<br>

## **Overview**<br>
"In today’s world, public content has never been more relevant. Data from customer reviews is being used as a tool to gain insight into consumption-related decisions as the understanding of its associated sentiment grants businesses invaluable market awareness and the ability to proactively address issues early.

Sentiment analysis uses a process to computationally determine whether a piece of writing is positive, negative, neutral, or mixed. This is usually used on social media posts and customer reviews in order to automatically understand if some users are positive or negative and why. Amazon Comprehend is a natural language processing (NLP) text analytics service made up of a handful of APIs that allows you to detect sentiment (along with key phrases, named entities, and language) and perform topic modeling from a collection of documents. The Amazon Comprehend training data set primarily consists of data found in product descriptions and consumer reviews from one of the largest natural language collections in the world — Amazon.com."
In this study, we will apply Natural Language Processing (NLP) by useing a machine learning algorithm to find insights and relationships in text (Amazon's customer reviews) to detect bad and good customer reviews. <br>



## **Goals**<br>
The goal of this study is to show how sentiment analysis can be performed on Amazon's Customer Reviews using python. For each textual review, we want to predict if it corresponds to a good review (the customer is happy) or to a bad one (the customer is not satisfied). The reviews overall ratings can range from 1 to 5.

<p align="center">
<img src="https://github.com/soheil-ra/NLP/blob/main/Images/image4.PNG?raw=true"  />
</p><br>

I try to achive the followings for this assignment:<br>

**1. Preparing Data -** This section includes, Cleaning, Exploring and Visualizing  data.<br>
**2. Proposing Methods & Experiments -** To perform the Text-Classification (NLP), I applied three different feature extraction models (Bag of Words, TF_IDF and Word Embedding) and compared the results of their prediction acuracies, by using Logistic Regression algorithm.
It needs to be mentioned that since document data is not computable, it must be transformed to numerical data such as vector space model. This transformation task is generally called feature extraction of document data.<br>
<br>

## **Motivation and Background**<br>
Sentiment analysis is an important concept and one of the most effective tools of improving the conversion rate. Reading the sentiment of consumers, not only enables businesses to reach out to their target audience, but also enables them understand their needs and feelings. It provides a bird-eye-view to brands and let them observe and protect their prestige. Additionally, it automates a cumbersome process of going through millions of lines of text to better read and listen to the demands and concerns of consumers. That, in turn, helps manage unpredictable damaging scenarios and ease the cost of doing so. Daily, weekly, and monthly reports of sentiment analysis can help a brand improve its image, set its pricing appropriately, and improving its relationship with consumers. It can also be turned into a tool of tracking sector-wide trends and demands, including competitors’ contents and strategies, to contribute to a competitive advantage.
<br>

<p align="center">
<img src="https://github.com/soheil-ra/NLP/blob/main/Images/image3.PNG?raw=true" />
</p>

## **Data**
The dataset has been collected from Kaggle (https://www.kaggle.com/aswin0821/amazon-reviews), and it's a .csv file consisting of information about 10,000 records of customers and 9 attributes, writing reviews on Amazon food product every day. Each review contains textual feedback along with a 1-to-5 star rating system (1 being least satisfied and 5 being most satisfied).<br>

Attribute Information:<br>

**1. ProductId** - ID of the referenced product by the customer. (categorical)<br>
**2. UserId** - registered user ID. (categorical)<br>
**3. ProfileName** - registered user profile name. (text)<br>
**4. HelpfulnessNumerator** - number of users who found the review helpful. (numerical)<br>
**5. HelpfulnessDenominator** - Number of users who voted whether the review was helpful or not. (numerical)<br>
**6. Score** - rating between 1 and 5. (ordinal)<br>
**7. Time** - timestamp of the review. (numerical)<br>
**8. Summary** - brief summary of the review. (text)<br>
**9. Text** - text of the review. (text)<br>
<br>

<pre>
Contributors : <a href=https://github.com/soheil-ra>Soheila Rahmani</a>
</pre>

<pre>
Languages    : Python
Tools/IDE    : Anaconda
Libraries    : pandas, numpy, matplotlib, seaborn, sklearn
</pre>

<pre>
Duration     : December 2020
</pre>
