Twitter Sentimental Analysis-NLP

It is a Natural Language Processing Problem where Sentiment Analysis is done by Classifying the Positive tweets from negative tweets by machine learning 
models for classification, text mining, text analysis, data analysis and data visualization

Dataset Informations

The objective of this task is to detect hate speech in tweets. For the sake of simplicity, we say a tweet contains hate speech if it has a racist or sexist sentiment associated with it. So, the task is to classify racist or sexist tweets from other tweets.
Formally, given a training sample of tweets and labels, where label ‘0’ denotes the tweet is racist/sexist and label ‘1’ denotes the tweet is not racist/sexist, your objective is to predict the labels on the given test dataset.

Preprocessing Of Dataset

The preprocessing of the text data is an essential step as it makes the raw text ready for mining, i.e., it becomes easier to extract information from the text and apply machine learning algorithms to it. If we skip this step then there is a higher chance that you are working with noisy and inconsistent data. The objective of this step is to clean noise those are less relevant to find the sentiment of tweets such as punctuation, special characters, numbers, and terms which don’t carry much weightage in context to the text.

User tags and URLs: 
For the purpose of sentiment analysis, the user tags (i.e., mentioning of other Twitter user accounts by using @) and URLs (i.e., a link to a specific website) convey no specific sentiment and were therefore replaced with a suitable placeholder (e.g. USER, URL). As a result, the presence and frequency of user tags and URLs were retained and normalized.

Hashtags: 
Hashtags are an important element of Twitter and can be used to facilitate a search while simultaneously convey opinions or sentiments. For example, the hashtag #love reveals a positive sentiment or feeling, and tweets using the hashtag are all indexed by #love. Twitter allows users to create their own hashtags and poses no restrictions in appending the hashtag symbol (i.e., #) in front of any given text. Following the example of the #love hashtag, we preprocessed hashtags by removing the hash sign, essentially making #love equal to the word love.

Lemmatization and uppercase words: 
For grammatical reasons, different word forms or derivationally related words can have a similar meaning and, ideally, we would want such terms to be grouped together. For example, the words like, likes, and liked all have similar semantic meaning and should, ideally, be normalized. Stemming and lemmatization are two NLP techniques to reduce inflectional and derivational forms of words to a common base form. Stemming heuristically cuts off derivational affixes to achieve some kind of normalization, albeit crude in most cases. We applied lemmatization, a more sophisticated normalization method that uses a vocabulary and morphological analysis to reduce words to their base form, called lemma. It is best described by its most basic example, normalizing the verbs am, are, is to be, although such terms are not important for the purpose of sentiment analysis. Additionally, uppercase and lowercase words were grouped as well.

Train and test a Sentiment Analysis model

Dataset is now divided into training and testing sets. The training set will be used to train the algorithm while the test set will be used to evaluate the performance of the machine learning model.Once data is split into training and test set, machine learning algorithms can be used to learn from the training data. Finally, to evaluate the performance of the machine learning models, we can use classification metrics such as a confusion metrix, F1 measure, accuracy, etc. 

Finally after the sentimental analysis model is created, now the negetive tweets can be further analysed for the various reason for the negetive tweets. We can rank the negetive tweets reason to get to know the reason and help the airlines to improve their services in that perticular areas. 
