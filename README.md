# Drug Reviews Sentiment Analysis
 
 Data source: https://archive.ics.uci.edu/ml/datasets/Drug+Review+Dataset+%28Druglib.com%29

# About the Dataset
The dataset is sourced by the author by crawling pharmaceutical review websites and records reviews and ratings of some drug brands by the consumers. Furthermore, reviews are grouped into reports on the three aspects benefits, side effects and overall comment. Different attributes about the drugs is also in the dataset like effectiveness of the drug

# Objective of the Study
The analytical exercise tries to run sentiment analysis on the reviews of the consumer about the drugs. Our primary variable of concern is Overall Reviews (commentsReview) which records the actual text posted on the website about the drug by the consumer. 
We run sentiment analysis on the review and try to understand the polarity of the comments through various python libraries

# Outcomes and Observations

## Useful Count and Ratings Distribution
![image](https://user-images.githubusercontent.com/98545133/190706922-6d69070c-3f7d-420f-a4a7-1d373f2fcfc1.png)
![image](https://user-images.githubusercontent.com/98545133/190706971-72a6d400-1ef6-4f8d-b29b-556c14a7b227.png)

### Observation
On an average, the comments we have in our data are having useful count at 2080, which means we are analysing comments which many people find useful and are geniune.
Rating for the medicines are also distributed between 5 to 9 and hence we see both experiences of consumers, good and bad.

## Polarity of Comments' Distribution
![image](https://user-images.githubusercontent.com/98545133/190707778-740c374d-8dc1-471c-8d16-e5d3555c9741.png)

### Observation
We observing a general trend of 75% of data staying in polarity range between 0 and 0.2 (mostly positive) across all the category of side effects. We could say that mostly the reviews about drugs have been either neautral or positive. Drugs with Severe Side Effects have majority outliers at negative polairty


## Distribution of Word Count of Reviews Accross Different Side Effects and Drug Effectiveness
![image](https://user-images.githubusercontent.com/98545133/190707987-65438151-70d8-483a-b8e3-af009fdcca7b.png)

### Observation
The distribution is right skewed, also called as Zipf Distribution. The word count of the comments for both categories (drug effectivness and drug's side effects) ranges from 0 to 50. Majority of customers express their reviews about the drug in 50 words and reviews with high word count occurs infrequently.

Drugs with Mild Side Effects and No Side Effects have more people commenting maybe since these must be used by many. Highly Effective drugs also attracts people's comments more.


## Scatterplot of Word count and polarity acrross various categories of side effects
![image](https://user-images.githubusercontent.com/98545133/190708065-769ef599-f68f-4487-8fd7-174131d1cf2a.png)

### Observation
A scatter plot between word count and polarity of reviews visualizes a non-liner relationship between the two vairables, which means that polarity of reviews can come in any number of words (it could be higher polarity in fewer words and vice-versa) The plot also enables us to visualize how the distribution of polarity looks like for reviews with word count greater than 50 words (the majority of reviewer word count) Reviews with word count over 50 are evenly distributed between -0.25 and 0.25 polarity.

