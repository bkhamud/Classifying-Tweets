# Classifying-Tweets
A common NLP task is to classify text. The most common text classification is done in sentiment analysis, where texts are classified as positive or negative. In this project, we will consider a slightly harder problem, classifying whether a tweet is about an actual disaster happening or not.

Not all tweets that contain words associated with disasters are actually about disasters. A tweet such as, "California forests on fire near San Francisco" is a tweet that should be taken into consideration, whereas "California this weekend was on fire, good times in San Francisco" can safely be ignored.

The goal of the task here is to build a classifier that separates the tweets that relate to real disasters from irrelevant tweets. The dataset that we are using consists of hand-labeled tweets that were obtained by searching Twitter for words common to disaster tweets.
