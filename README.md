# Sentiment-Anlaysis-on-Yelp-Dataset
Hello there, Welcome!
Have you ever asked yourself if it was possible classify test automaticly with python ? 

Well, this is a project about sentiment analysis were the task is to classify, in this case, the reviews of clients on restaurants in which they go using Pyspark.
The dataset used here was the Yelp's one which is a data of client's review on restaurants mainly in United state and Canada( as we observed it during data visualization). 

So, in the first time, we analysed the different data by visualizing it. After this step, we cleaned their reviews with nltk and moved to machine learning task with MLlib. 

The models used there were Logistic Regression and Naive Bayes. The task of classification was done with pipelines as it allows to optimise the time (The dataset is huge and that's why we decided to work with Pyspark).

You can check the colab Notebook directly here: https://colab.research.google.com/drive/1VoICrAJUd6addT-0HlHV1NcnK6ErxEfE?usp=sharing
