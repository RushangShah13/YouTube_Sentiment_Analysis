# YouTube-Sentiment-Analysis

To start with it make sure to get the api keys of Youtube. 

Scrape all the YouTube comments using api.

## Description :
This project works by scraping YouTube comments and identify the sentiment of comments.

The directory FancySentiment will be used to develope the WordCloud of the comments which will be made by the frequenly used words in comments. 

The directory CommentSentiment will be used to show the positive/negative sentiment of the comments.

## Prerequisites : -
_Python 3_

_pip(Python Package Index) :_

> $ sudo apt-get install python3-pip

_requests package :_

> $ sudo pip3 install requests

_lxml package :_

> $ sudo apt-get install libxml2-dev libxslt1-dev python-dev

> $ pip3 install lxml

_matplotlib package :_

> $ sudo pip3 install matplotlib

_nltk package :_

> $ sudo pip3 install nltk

_wordcloud package :_

> $ sudo pip3 install wordcloud


## Flow to run the files : -
-> First input the __API key__ in the file.

-> Run __CommentSentiment/comment_extract.py__(_To extract the comments with the help of API_)

->Then run __FancySentiment/comment_downloader.py__(_To build the wordcloud_)

-> Then run the __driver.py__ file.(_To find the sentiment of the comments for the specific video_) 
