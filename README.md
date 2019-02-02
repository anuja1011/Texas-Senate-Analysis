# Texas-Senate-Analysis

****************************************************************************
I have been leaning on how to do Text Analytics and Natural Language Processing on wide platform of social media like Public Forums (Edmunds, Yelp etc.), Instagram, Twitter etc.

This is the first Project of the Series #User-Generated-Content-Analysis. Since this is a learning process, you will see a gradual improvement in the techniques used and also reduction in the number of assumption. 

As for this project: 

Things Learned:
* Lift Calculation
* Word-Frequency count
* Natural Language Processing
* Stemming & Lemitization
* Importance of word replacement
* Sentiment Analysis
****************************************************************************

# Project 2 of Series #User-Generated-Content-Analysis

The aim of this project is to gain insights about the candidates in Texas Senate i.e. Beto and Cruz. The assumption is that the tweets will help us analyze the issues that people are relating to these candidates. The sentiment analysis will also reveal that which issues are related negatively while which issues are related positively. The same analysis is done for different cities in Texas. This inturn will help in deciding what should be the focus of Beto & Ted in large cities vs the small cities. Also, in which area do they need to gear up and which is there strong point.

The flow of this project goes as follows:

* Collect 4k-5k tweets on the 2018 Texas Senate race. These tweets are collected at different time periods so that broad scope of tweets can be covered. While searching for tweets keywords like "#TexasSenate, #TexasSenate2018." It is preferable to use general hashtags and search keywords (like Texas Senate Race) rather than “Beto” or “Cruz” 

* Pre-processing of data which includes removing of stop words, punctuations etc. Deleting redundant tweets i.r duplicate tweets followed by frequency count and word replacement .

* One of the important steps is identification of issues like crime, jobs, terrorism etc. To do this the frequency count of words is analyzed and 4-5 categories of issues are formed. Once the issue topics are finalized those words are replaced by the issues. This is done so that the association can be found between electoral candidates and issues.

* Next step is to perform lift calculation and identify the sentiment scores between issues and candidates whereever lift score is greater than 1. The sentiment score gives the notion in which people are relating the issues to the candidates.

* The whole analysis is done for both big and small cities in Texas to understand the prevailing notion in Texas as a whole as well as specific cities.

* The key idea behind this project is to come up with advice for two candidates for their election strategies. The key things they should focus on, what are their opportunities and what are their threats. What should be their winning strategies and in which cities who has a strong hold.
