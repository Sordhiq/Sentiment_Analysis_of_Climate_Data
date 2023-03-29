# Sentiment Analysis of Climate Data
With growing global concerns around the devastating effects of climate change and global warming, this project is aimed at classifying tweeter data inorder to comprehend the sentiment/perception of the sampled audience about climate change. 

The classification script set out with importing necessary python libraries and classes such as pandas, numpy, scikit-learn, re, wordcloud and NLTK, which would be needed during the course of the classification. This was closely followed with loading the train, test and sample datasets and examining the first five rows of the data to have an overview of its nature and contents.

Next was applying descriptive statistics and visualization inorder to see variations and help with visual storytpreprocessing where punctuations, urls and unwanted characters were removed to obtain a clean string. Next was Tokenizing the data using the TweetTokenizer class and stemming them back into their root words using the Stemming class. Afterwards, the tweets were converted into numerical data type using the CountVectorizer class.

The tweet was further splitted into train and test data using the train_test_split function and subsequently standardized using the StandardScalar class. Next was instantiating all of the 6 classification models to be attempted in building this solution. The instantiated models were further fitted with accuracy and classification metrics such as accuracy score, recall and f1-score, obtained to assess the performance of the model.

At the end of the project, it could be deduced that more people are becoming climate-conscious and are beginning to leverage social media in holding such burning discussions and clamour for climate justice. Similar, recurring words as contained in the Wordcloud could help climate-smart companies in building climate-smart products and helping tailoring information/commercials to their target audience.



With growing global concerns around the devastating effects of climate change and global warming, this project is aimed at classifying tweeter data inorder to comprehend the sentiment/perception of the sampled audience about climate change. 

The classification script set out with importing necessary python libraries and classes such as pandas, numpy, scikit-learn, re, wordcloud and NLTK, which would be needed during the course of the classification. This was closely followed with loading the train, test and sample datasets and examining the first five rows of the data to have an overview of its nature and contents.

Next was applying descriptive statistics and data visualization inorder to see dimensions, variations and help with visual storytelling. Preprocessing was subsequently done to remove punctuations, urls and unwanted characters from the tweet data. Next was Tokenizing the data using the TweetTokenizer class and stemming them back into their root words using the Stemming class. Afterwards, the processed tweets were converted into numerical data type using the CountVectorizer class.

The tweet was further splitted into train and test data using the train_test_split function and subsequently standardized using the StandardScalar class. Next was instantiating 6 (Logistic Regression, Naïve Baye, Support Vector Classification, Random Forest and K-Nearest Neighbors) classification models and 1 ensemble technique (Boosting method) to be attempted in building the model solution. The instantiated models were further fitted with accuracy and classification metrics such as accuracy score, recall and f1-score, obtained to assess the performance of the model.

At the end of the project, it could be deduced that more people are becoming climate-conscious and are beginning to leverage social media platforms in holding such important discussions and clamouring for climate justice. Similar, recurring words as contained in the Wordcloud could help climate-smart companies in building climate-smart products and helping tailoring information/commercials to their target audience.



