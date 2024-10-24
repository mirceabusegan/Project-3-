# Group3Project3
The code is found in the Sentiment_Analysis_final.ipynb
### Overview
  We used the NLTK library in order to use sentiment analysis on news articles pertaining to stocks. The library has an automized system that analyzes the polarity scores of these articles between scores if -1 to +1. The closer it is to +1, the better the news is perceived by people and readers. We will use this information to compare it agaisnt the current stock price and see if there is any correlation between news titles and stock prices. The purpose of this project is to study the outcome charts and see what the relationship is between the scores and the price. It can help determine how valuable news are in determining future stock prices. 

## Instructions 
  The project can be used by updating the stocks that are relevant to you in the tickers list. then run the code once every day in order to get updated charts with the scores for every day and prices for those days. It is currently set to show a week of data, but it can be adjusted to show a month or even longer to get a better readind of the data. 

## ethical considerations 
  We did not come across many ethical issues in our project, but the only possible ethical issue might be that we scraped the data from the web and did not use an api issued directly from the news source. Maybe it would be better and more ethical to get permission to use these articles. 

## References for Data Sources 
  We used finviz in order to scrape the news articles and run them in the sentiment analysis. 
  - https://finviz.com/
  
  We also used the yahoo finance platform through a library within python to access the prices.
  - https://finance.yahoo.com/

## References for code used that is not our own
  We got help from a youtube video that used sentiment analysis as well. 
  - https://www.youtube.com/watch?v=o-zM8onpQZY&t=585s

