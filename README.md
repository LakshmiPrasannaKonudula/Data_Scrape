# Twitter Scraper
The code can be used to scrape tweets from twitter into a Database which can be  then dumped into a CSV.  
Step1: Install the required packages mentioned in requirements.txt using the below command
* `pip install -r requirements.txt`
Step2: 
* Create a file `private.py` in the directory.
* From Twitter developer account extract the following keys and edit them in private.py
    * `TWITTER_KEY`(access token)
    * `TWITTER_SECRET`
    * `TWITTER_APP_KEY`
    * `TWITTER_APP_SECRET`
    * `CONNECTION_STRING` = "sqlite:///tweets.db" 
Command line queries:

* `python scrape.py` to scrape.  Use `Ctrl + C` to stop.
* `python dump.py` to generate `tweets.csv`, which contains all the tweet data that was scraped.
* To modify keywords and date change the values in `settings.py`.
