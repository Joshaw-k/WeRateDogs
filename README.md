# WeRateDogs Data Exploration
## by Emefiele-Konyeri Awinrin
## Dataset
WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. The account was started in 2015 by college student Matt Nelson, and has received international media attention both for its popularity and for the attention drawn to social media copyright law. This archive contains basic tweet data (tweet ID, timestamp, text, etc.) for all 5000+ of their tweets as they stood on August 1, 2017. There are three dataset to be explored in this data analysis, which would be wrangled for proper exploration of the data, analysed to find patterns and trends, and visualize the insights gained through charts and graphs.

> This project has two main parts

1. In Part I, Exploratory data visualization, i used use Python visualization libraries to systematically explore this dataset(consists of information regarding 2,174 tweets from the WeRateDogs Twitter account with 21 attributes columns), starting from plots of single variables and building up to plots of multiple variables.

> The WeRateDogs data consists of 2,174 tweets and 21 features('tweet_id', 'timestamp', 'source', 'text', 'rating_numerator',
       'rating_denominator', 'name', 'stage', 'jpg_url', 'img_num', 'p1',
       'p1_conf', 'p1_dog', 'p2', 'p2_conf', 'p2_dog', 'p3', 'p3_conf',
       'p3_dog', 'retweet_count', 'favorite_count'), after data cleaning the dataset was transformed to 24 features(additional features: 'hour', 'month', 'date').
       
2. In Part II, Explanatory data visualization, i produced a short presentation that illustrates interesting properties, trends, and relationships that were discovered in my dataset. The primary method of conveying my findings were through transforming my exploratory visualizations from the first part into polished, explanatory visualizations.

## Summary of Findings

* Most of the tweets in the dataset did not contain a dog stage, but for the tweets containing a dog stage pupper seems to be the most popular dog stage in the dataset followed by doggo
* The Frequent occuring rating numerators are within the range of 7 to 15 with 12 the most frequent rating and 7 the least.
* The distribution of the favorite counts across 2017 shows that the most common favorite counts is within 0 favorite count to around 3,500 favorite counts
* The distribution of the retweets counts across 2017 shows that the most common retweets counts is within 0 favorite count to around 900 retweets counts
* There are more counts of image number one probably most tweets only have one image, the tendency to have more images is actually low.
* Rating 14 had the highest average favorite count and retweet count followed by rating 13.
* There is a positive correlation between favorite count and retweet count, which obviously mean if people favorite the tweet then there is a high tendency they would retweet it.
* Engagements(favorite count and retweet count) are at a peak at 13.00PM and uninteractive hours from 4:00AM to 11:00AM
* Engagements are high during the fourth quarter into the year.
* There is a continuous decrease in number of tweets from late 2015 to third quarter of 2017
* Image 4 has the highest average confident prediction for p1_conf,image 1 has the highest average confident prediction for p2_conf and p3_conf respectively.
* There is a negative correlation in first chart(p1_conf and p2_conf), negative correlation in second chart(p1_conf and p3_conf), postive correlation in third chart(p3_conf and p2_conf)

## Key Insights for Presentation

For this presentation i will be unveiling the most popular dog stage, the most common ratings, rating with the highest average favorite count and retweet count, correlation between favorite count and retweet count, the period of time with high engagements and the growth of interactions along the years.