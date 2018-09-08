# Tweet Analyzer

## What is the Twittersphere's current opinion of _______?

### Type in a seach word and find out if Twitter has overall negative or positive things to say about it.

#### Quick set up

requires [python]("https://www.python.org/downloads/release/python-370/")

- clone repo

set up secret keys:
- [Apply]("https://developer.twitter.com/en/docs/tweets/search/api-reference") for access to Twitter's Standard Search API.
- create a file called keys.py in tweet-sentiment-analyzer/tweet-analyzer/text-analyzer
- copy the contents of tweet-sentiment-analyzer/tweet-analyzer/text-analyzer/keys_sample.py into your keys.py folder with your  newly acquired Twitter API credentials
- cd back to the root directory
- source env/bin/activate
- cd tweet-analyzer
- pip install requirements.txt
- python3 manage.py runserver
- cd client
- npm install
- npm start

go to http://localhost:3000 to see the running app
