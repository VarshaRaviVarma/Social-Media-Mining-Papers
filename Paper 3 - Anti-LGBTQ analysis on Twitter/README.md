## “ANTI - LGBTQ ANALYSIS ON TWITTER”

## Research Question
Approximately what percentage of twitter users are non-supporters of the LQBTQ community?

## Background
The rapid growth of social media has led to more and more people expressing their opinions online. Anyone can freely express their opinions on social media. Opinions can be positive or negative on a topic, with positive sentiments expressing a good opinion, while negative sentiments express a bad opinion. As a result, we are encouraged to utilize Twitter social media as a source of data, which will then be analyzed via sentiment analysis, which is a method of assessing, extracting, and processing textual data automatically to determine the sentiment expressed in an opinion. Given that most people in this generation support the LGBT community, it goes without saying that there are also those who are opposed to it. The LGBT community has been fighting for equal rights for a very long time and it is also safe to say that the newer generations have been increasingly supportive as time progresses. The question is, what is the percentage of users who are anti-LGBTQ on Twitter in the present? In this study, we will use sentiment analysis of Twitter tweets to determine the percentage of anti-LGBTQ twitter users.

## Data
Source: Twitter APIs extracted from twitter platform using Tweepy. Using Tweepy we can extract tweets based on specific words and therefore to extract LGBTQ related tweets, we use keywords like 'LGBTQ', 'Gay', 'Lesbian', 'Trans', etc. to retrieve tweets and build a dataset.

Content: The training dataset will be stored in a csv file containing 3 columns (API id, tweet text extracted using the API id, and labels) and testing dataset will initially have 2 columns (API id and tweet text extracted using the API id) which will be used by the trained model to predict the labels and obtain study results.

Size: 1000 tweets as training dataset and another set of 1000 tweets as testing dataset.

Time frame: Latest 7 days (most recent).

## Method
The study employs 'sentiment analysis' as its research method.
Using Tweepy, we can extract 2000 tweets related to LGBTQ issues through the Twitter platform. The tweets can be divided and stored in two CSV files, namely training data (1000 self-labeled tweets) and testing data (1000 unlabeled tweets). By using a Naive Bayes prediction model, the algorithm can be trained on the labeled training dataset, and then used to predict labels for the testing dataset. Label 1 indicates a positive tweet, while label 0 indicates a negative tweet. Using the model, the tweets will be categorized into two categories, positive and negative. With the help of this model, we can perform an analysis to determine the percentage of hateful opinion expressed towards LGBTQ individuals in the modern age.

## References
[1] Fahrur Rozi, Imam, Sholeh Hadi Pramono, and Erfan Achmad Dahlan. (2012) “Implementasi Opinion Mining (Analisis Sentimen) untuk Ekstraksi Data Opini Publik pada Perguruan Tinggi [Title in English: The Implementation of Opinion Mining to Extract Public Opinion Data in Higher Education].” Jurnal EECCIS 37. 

[2] Veny Amilia Fitri, Rachmadita Andreswari and Muhammad Azani Hasibuan, “Sentiment Analysis of Social Media Twitter with Case of Anti-LGBT Campaign in Indonesia using Naïve Bayes, Decision Tree, and Random Forest Algorithm”, 2019.

[3] Matilda Hansen, Emma Kavanagh, Eric Anderson, Keith Parry & Jamie Cleland (2022) An analysis of responses on Twitter to the English Premier League’s support for the anti-homophobia rainbow laces campaign, Sport in Society, DOI: 10.1080/17430437.2022.2028774 
