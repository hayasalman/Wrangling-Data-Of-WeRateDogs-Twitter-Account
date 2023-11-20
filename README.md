## Wrangling Data Of **WeRateDogs** Twitter Account

![weratedogs__](https://github.com/hayasalman/Wrangling-Dataset/assets/71796909/cee95e5b-7fda-4bf8-a0d7-73f41284147b)

## Overview 

Real-world data rarely comes clean. Using Python and its libraries, we will gather data from a variety of sources and in a variety of formats, assess its quality and tidiness, then clean it. This is called data wrangling. And the dataset that we will be wrangling is the tweet archive of Twitter user **(@dog_rates)**. 
WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. The account was started in 2015 by college student Matt Nelson, and has received international media attention both for its popularity.

## About The Dataset

- This dataset contains basic tweet data (tweet ID, timestamp, text, etc.) for all 5000+ of their tweets as they stood on August 1, 2017.
  
- Data sources stored in different formats and can be accessed through this links :

  - [Image Predictions TSV File](https://github.com/hayasalman/Wrangling-Dataset/blob/main/Datasets/image-predictions.tsv)
 
  - [Tweets JSON File](https://raw.githubusercontent.com/hayasalman/Wrangling-Dataset/main/Datasets/tweet_json.txt)
 
  - [Twitter Archive Master CSV File](https://github.com/hayasalman/Wrangling-Dataset/blob/main/Datasets/twitter_archive_master.csv)
 
  - [Twitter Archive Enhanced CSV File](https://github.com/hayasalman/Wrangling-Dataset/blob/main/Datasets/twitter-archive-enhanced.csv)
 
  ## Coding

  -  Python Integrated Development Environment (IDE) : Jupyter Notebooks.

   **Packeges used**
   
  * **pandas - numby** : used for data manipulation.
  * **matplotlib** : used for data visualization.
  * **requests** : used for HTTP requests.
  * **os** : used for interacting with the operating system.
  * **tweepy** : used for accessing the Twitter API.
 
  ## Approaches & Methodologies

  - **Gathering data** : the first step of data wrangling is to collect data from different sources.
 
  - **Assessing data** : : assessing the data both visually & programmatically to discover any quality\tidiness issues. The four main data quality 
      dimensions are: Accuracy, Validity, Completeness Consistency , while the structural issues related to tidiness issues.
    
  - **Cleaning data** : after the data assessment we will start to clean it from the quality\tidiness issues that we found before.
 
  - **Storing data** : we need to store the cleaned dataset into a new csv file called twitter archive master before we analyze it.
 
  - **Analyzing , and visualizing data** : by performing graphical and non-graphical exploratory data analysis.
 
  - **Communicating the findings** : through communicates all the insights and displays the visualization(s) produced from your wrangled data.
 
  ## Business Insights

  - There're **534 tweets with more than 10,000 favorites** in this dataset, and there are **83 tweets with more than 10,000 retweets**. In fact, we 
    found that the most favorite tweet has **132,810 favs**, while the most retweeted tweet has **79,515 retweets**.
 
  - **Charlie** is the most common dog name, then **Oliver, Lucy and Cooper**. Whereas, these names: **Blipson, Millie & Carter** are less common.

  - **The golden retriever** is the most common dog breed in this dataset where there's **151 dogs of this breed**. After it there's **104 Labrador 
    retrievers**, then **93 dogs of Pembroke and 85 dogs of Chihuahua**.

  - **The Twitter Web Client and TweetDeck** are rarely used sources. While, the most source used to generate the tweets is **Twitter for iPhone**.

  ## References

  - [Wrangling Twitter API Data Project File](https://github.com/hayasalman/Wrangling-Dataset/blob/main/Wragling_Act_.ipynb)

  

