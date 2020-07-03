# Emotional Tweets Covid19

This is an AI project focused on users-society reactions through social networks (twitter) about covid 19 in Mexico.

With sentiment and topic analysis algorithms, it will be able detect to concerns of people related to the health contingency and user activities.

## Data required to run locally
Once downloaded the master branch, download below free for distribution datasets of tweets, or use your owns data. It will be used to predict emotions and generate a modeling topic.

https://www.kaggle.com/smid80/coronavirus-covid19-tweets-early-april \
https://www.kaggle.com/smid80/coronavirus-covid19-tweets-late-april \
https://www.kaggle.com/smid80/coronavirus-covid19-tweets


## Build with

Python 3.7.6

The main modules used are described below, ensure you have downloaded the same.

* <a href="https://pandas.pydata.org/"> pandas </a> (1.0.1) - To use data structures and data analysis tools.
* <a href="https://matplotlib.org/"> matplotlib </a> (3.1.3) - They are used to create the analysis graphs, applying some statistics.
* <a href="https://www.datacamp.com/community/tutorials/wordcloud-python"> wordcloud </a> (1.7.0) - An image consisting of words used in tweets is created, in which the size of each word indicates its frequency or importance.
* <a href="https://numpy.org/"> numpy </a> (1.18.1) - High-efficiency multi-dimensional arrays designed for scientific calculation
* <a href="https://www.nltk.org/api/nltk.corpus.html"> nltk </a> (3.4.5) - With nltk corpus we download a dictionary of unnecessary words in Spanish that will help us clean up tweets (stopwords). We will also use it to generate “tags” for Spanish words with “StanfordPOSTagger”. This method of filtering words using tags in addition to the stopword.
* <a href="https://pypi.org/project/pyLDAvis/"> pyLDAvis </a> (2.1.2) - To visualize our modeling of topics.
* <a href="https://pypi.org/project/gensim/"> gensim </a> (3.8.3) - With gensim we will create the corpus to generate the LDA (topic modeling)
* <a href="https://plotly.com/python/"> plotly </a> (4.8.2) - We will use plotly libraries to make a line graph, in this case for the visualization of the prediction of tweets categorized by day in a timeline.

Execute the notebooks on this order:

1. EDA.ipynb
2. Clean Data.ipynb
3. Train sentiment analysis model.ipynb
4. Predict Sentiment Tweets.ipynb
5. Topic Modeling for Tweets.ipynb

## Sample Result Visualizations
**MX Twitts Positive vs Negatives per Day**

![](https://i.imgur.com/5Vwdbq3.png)

**Positive word cloud**

![](https://i.imgur.com/ZvKuX9P.png)

**Negative word cloud**

![](https://i.imgur.com/C6772MH.png)

**Modeling Topic**

![](https://i.imgur.com/TCov8Gl.png)


## Team
Jorge Alfredo Sanchez Lamas \
Gabriela Jimenez \
Francisco Gonzalez \
Cesar Ramon \
Alfredo Bello 

## Acknowledgments
Thanks to <a href="https://www.saturdays.ai/"> Saturday AI </a> community we had the formation and fundamental learning on AI fields and concluding with this demo project.

Thanks also specially to our mentor: Gibran Felix Zavala.
