 <H2 align="center">Sentiment Analysis of Amazon Electronic Products Reviews </H2>
 <H1 align="center", size= 3>NLP (Natural Language Processing)</H1>


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

**5. Dataset -** [Dataset](https://github.com/soheil-ra/NLP/blob/main/Amazon%20Product%20Reviews.csv) <br>
**6. Code -** [Code](https://github.com/soheil-ra/NLP/blob/main/NLP_Report.ipynb)<br>
**7. Images -** [Images](https://github.com/soheil-ra/NLP/tree/main/Images)<br>

## **Overview**<br>
"In today’s world, public content has never been more relevant. Data from customer reviews is being used as a tool to gain insight into consumption-related decisions as the understanding of its associated sentiment grants businesses invaluable market awareness and the ability to proactively address issues early.

Sentiment analysis uses a process to computationally determine whether a piece of writing is positive, negative, neutral, or mixed. This is usually used on social media posts and customer reviews in order to automatically understand if some users are positive or negative and why. Amazon Comprehend is a natural language processing (NLP) text analytics service made up of a handful of APIs that allows you to detect sentiment (along with key phrases, named entities, and language) and perform topic modeling from a collection of documents. The Amazon Comprehend training data set primarily consists of data found in product descriptions and consumer reviews from one of the largest natural language collections in the world — Amazon.com."
In this study, we will apply Natural Language Processing (NLP) by using a machine learning algorithm to find insights and relationships in text (Amazon's customer reviews) to detect bad and good customer reviews. <br>



## **Goals**<br>
The goal of this study is to show how sentiment analysis can be performed on Amazon Customer Electronic Products Reviews using python. For each textual review, we want to predict if it corresponds to a good review (the customer is happy) or to a bad one (the customer is not satisfied). The reviews overall ratings can range from 1 to 5.

<p align="center">
<img src="https://github.com/soheil-ra/NLP/blob/main/Images/image4.PNG?raw=true"  />
</p><br>

I try to achive the followings for this project:<br>

**1. Preparing Data -** This section includes, Cleaning, Exploring and Visualizing  data.<br>
**2. Proposing Methods & Experiments -** To perform the Text-Classification (NLP), I applied four different feature extraction models (Bag of Words, TF_IDF, Word Embeddings and Topic modeling) and compared the results of their prediction accuracies, using Logistic Regression and Linear Support Vector Machine Algorithms.
It needs to be mentioned that since document data is not computable, it must be transformed to numerical data such as the vector space model. This transformation task is generally called feature extraction of document data.<br>

## **Motivation and Background**<br>
Sentiment analysis is an important concept and one of the most effective tools of improving the conversion rate. Reading the sentiment of consumers, not only enables businesses to reach out to their target audience, but also enables them to understand their needs and feelings. It provides a bird-eye-view to brands and let them observe and protect their prestige. Additionally, it automates a cumbersome process of going through millions of lines of text to better read and listen to the demands and concerns of consumers. That, in turn, helps manage unpredictable damaging scenarios and ease the cost of doing so. Daily, weekly, and monthly reports of sentiment analysis can help a brand improve its image, set its pricing appropriately, and improve its relationship with consumers. It can also be turned into a tool of tracking sector-wide trends and demands, including competitors’ contents and strategies, to contribute to a competitive advantage.
<br>

<p align="center">
<img src="https://github.com/soheil-ra/NLP/blob/main/Images/image3.PNG?raw=true" />
</p>

## **Data**
The dataset has been collected from https://data.world/datafiniti/amazon-and-best-buy-electronics website and is a .csv file with the size of 8.29 MB, consisting of information of over 7,000 online reviews for 50 electronic products from websites like Amazon and Best Buy provided by Datafiniti's Product Database.  This dataset has 20 attributes, writing reviews on Amazon electronic products every day. Each review contains textual feedback along with a 1-to-5-star rating system (1 being least satisfied and 5 being most satisfied). 
Note that this is a sample of a large dataset. The full dataset is available through Datafiniti.   
Attribute Information:<br>

**1. id** - (text)<br>
**2. asins** - (text)<br>
**3. brand** - (text)<br>
**4. categories** - (text)<br>
**5. colors** - (text)<br>
**6. dateadded** - (timestamp)<br>
**7. dateupdated** - (timestamp)<br>
**8. dimension** - (text)<br>
**9. manufacturernumber** - (text)<br>
**10. name** - (text)<br>
**11. primarycategories** - (text)<br>
**12. reviews_dateSeen** - (text)<br>
**13. reviews_doRecommend** - (boolean)<br>
**14. reviews_numhelpful** - (numerical)<br>
**15. reviews_rating** - (numerical)<br>
**16. reviews_sourceUrls** - (url)<br>
**17. reviews_text** - (text)<br>
**18. reviews_title** - (text)<br>
**19. reviews_username** - (text)<br> 
**20. weight** - (text)<br> 
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
Duration     : June 2021
</pre>
