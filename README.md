# News Sentiments of a Presidential Campaign

### Objective

Sentiment analysis of various news mediums around the 2016/Nov/8 US presidential elections.
The main questions we want to ansewer:
* Which candidate dominated the media space?
* What topics were the main drivers in the public discourse? How they affected the candidates?
* Are the left and right leaning mediums biased?
* Is the "emotional charge" of a traditional and a tabloid-like medium demonstrably different?


### Data Set

* News article headlines from the left-centrist New York Times and the right-leaning Fox News
* Timeframe: 2016 October 1 - 2016 November 30 (Roughly one month before and after the Nov 8 elections)
* We gathered the - 3 (Fox) and 10 (Nyt) - most relevant headlines for each day for both candidates seperately
* Full dataset is about 1550 headlines


### Tools and Methods to be used

* Python and Pandas for data gathering and wrangling
* API in the case of New York Times and manual collection for Fox News
* NLP and Sentiment analysis with VADER

Methodology:

* We used text cleaning and NLP to find the most frequent words for given time periods and see which topics and candidates dominated
* We used the VADER library to calculate and aggregate the polarity (how negative or positive a text is) of the headlines
