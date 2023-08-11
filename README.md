# Sentiment-Analysis
## Sentiment Analysis Review ChatGPT

As the name suggests, it means to identify the view or emotion behind a situation. It basically means to analyze and find the emotion or intent behind a piece of text or speech or any mode of communication.

We, humans, communicate with each other in a variety of languages, and any language is just a mediator or a way in which we try to express ourselves. And, whatever we speak or write, has a sentiment associated with it. It might be positive or negative or it might be neutral as well.

As we know, with the development of technology, there are many AI technologies that can help humans work, one of which is ChatGPT. Until now, this technology has still raised pros and cons because it is felt that it can backfire on humans themselves. Some people say that AI technology will replace all human jobs, thus threatening their livelihoods.

Here I will try to analyze public sentiment towards ChatGPT. The data I took came from https://www.kaggle.com/datasets/saloni1712/chatgpt-app-reviews. 

### The following are the steps taken in this project

1. Prepocessing Data
Data preprocessing is very important so that the resulting analysis is better. In this process, Convert Uppercase to Lowercase, Remove
links, Remove Punctuations, Remove Number, Remove Stopwords and Stemming are performed. You can use the Preprocessing Data.ipynb file as
reference for the data preprocessing process.
![EEG Band Discovery](/assets/pie chart.png)

3. Sentiment Analysis Using Support Vector Machine Model
In this stage, the support vector machine model is built. You can use Sentiment_Analysis_SVM.ipynb for reference. In this section, the trained model is also used to predict unlabeled reviews. After the prediction, I made a pie chart visualization to see the percentage comparison of each sentiment class.


