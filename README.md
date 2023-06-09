# Tweepy Twitter Tweet Scraper Sample - Python
A tweet scraping program that fetchs tweets with specific keywords using Python, the Tweepy library and the Twitter API (which is sadly no longer free unless you need to use read-only access)

## How To Use
**NOTE** This assumes you have Python 3.x installed (have tested on 3.10 and higher) and that you know how to use pip in the terminal
<br> <br> 1.) Install Tweepy using the following command
<code> pip install tweepy </code>
<br> 2.) Create an API application in Twitter Developer Centre
<br> 3.) Obtain the API key, secret key, access token, secret access token and bearer token and paste each into their respective lines in the data_collection.py file
<br> 4.) Run the data_collection.py file to retrieve and write scrapped tweets into a text file
<br> 5.) Install the vader sentiment analysis library in the terminal as following <code> pip install vaderSentiment </code>
<br> 6.) Run the analysis.py file on the text file generated by the data_collections.py file. You may tweak the code to fetch your desired data.
