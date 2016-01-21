News Bot

Description:
 
News Bot was created using ruby on rails, sidekiq, redis, and uses nokogiri, diffbot, alchemyAPI and a variety of other gems. The main purpose of the app was to scrape data from news articles, and also attempt to return a positive/negative sentiment score from Alchemy API in terms of the content coming from each article. It allows you see biases between news sources regarding current topics. The categories branch of the project also adds a crawling feature, aka it will take the first 10 news articles from a yahoo search and add them to the project, in addition to adding 'topics' so that users are able to create unique topics that they can watch and view the scores for. One of the major difficulties in the project was working to make sure that diffbot was able to pull back data from each article (some articles contain videos, or URL's that don't function with diffbot).


Authors:

Madeline Bagby
Ian Stalter
Tony Nguyen


![alt tag](https://github.com/Mbagby/NewsBot/blob/master/photos/Screen1.png)
![alt tag](https://github.com/Mbagby/NewsBot/blob/master/photos/Screen2.png)
![alt tag](https://github.com/Mbagby/NewsBot/blob/master/photos/Screen3.png)