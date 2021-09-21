# Sentiment_Analysis_NN

## Analyzing Stock Sentiment from Twits

## Introduction:

When deciding the value of a company, it's important to follow the news. For example, a product recall or natural disaster in a company's product chain. You want to be able to turn this information into a signal. Currently, the best tool for the job is a Neural Network.

For this project, you'll use posts from the social media site StockTwits. The community on StockTwits is full of investors, traders, and entrepreneurs. Each message posted is called a Twit. This is similar to Twitter's version of a post, called a Tweet. You'll build a model around these twits that generate a sentiment score.

We've collected a bunch of twits, then hand labeled the sentiment of each. To capture the degree of sentiment, we'll use a five-point scale: very negative, negative, neutral, positive, very positive. Each twit is labeled -2 to 2 in steps of 1, from very negative to very positive respectively. You'll build a sentiment analysis model that will learn to assign sentiment to twits on its own, using this labeled data.

## Requirements:

- Pytorch library latest version
- Numpy 
- Pandas
- NLTK and re library

## Contents:

1. Preprocess the Data
2. Create Bag of Words
3. Calculate the frequency of words appearaing in messages
4. Updating Vocabulary by Removing Filtered Words¶
5. Balancing the classes¶
6. Neural Network (LSTM and word Embeddings)
7. Training
8. Validation of the model
9. Making Predictions
10. Testing 

Acknowledgement:

I thank Udacity online platfrom for providing me the opprotunity to learn deep learning and neural network for sentiment analysis and several other problems. It was great opportunity learn Artificial Intelligence for Trading and obtain Nano Degree program. 
