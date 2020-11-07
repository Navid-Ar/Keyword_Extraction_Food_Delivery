# Food Delivery platform sentiment analysis
* 6000 reviews on Uber eats were scraped form google store.
* A machine learning model was built to asses reviews with the accuracy of 100.
* A skipgram analysis was performed on keras (tensorflow) to get the embeding layer (vector representation of the words). 
* The most repeated phrases in the negative and positive reviews were extracted and analyzed.



## Code and resources used
* Python Version:** 3.7
* Packages:** pandas, numpy, scikitlearn, tensorflow, keras, re, nltk, matplotlib, seaborn, flask, selnium, gensim

## Web Scraping
Tweaked the web Scraper to scrape 10000+ job postings from https://play.google.com/store. 6000 reviews with the following inofrmation were scraped:
* Feedback
* Rating


## Data Cleaning
After scraping the jobs from glassdoor, data cleaning was performed:
* Numbers were extracted from the rating column.
* Netural reviews (those with the rating of 3 out of 5) were removed from the df.
* Punctuations and stop words were removed from reveiws
* Numbers and emojies were dropped from the reviews.

