# Twitter-Sentiment-Analysis-version2020

Introduction
The ability to categorize opinions expressed in the text of tweets—and especially to determine whether the writer's attitude is positive, negative, or neutral—is highly valuable. In this guide, we will use the process known as sentiment analysis to categorize the opinions of people on Twitter towards a hypothetical topic called #hashtag.

There are different ordinal scales used to categorize tweets. A five-point ordinal scale includes five categories: Highly Negative, Slightly Negative, Neutral, Slightly Positive, and Highly Positive. A three-point ordinal scale includes Negative, Neutral, and Positive; and a two-point ordinal scale includes Negative and Positive. In this guide, we will use a three-point ordinal scale to categorize tweets.

# Getting Started
Sentiment analysis involves natural language processing because it deals with human-written text. You'll have to download a few Python libraries to work with the code. Use pip install <library> to install them.

Setting Up
To train a machine learning model, we need data.
Loading the Dataset etc

# How to get it running on your system (just incase you don't know how to)
- Clone or download this repository from Github
- Open it up in Pycharm
- Insert your API, API Secret, Access Token, Access Token Secret in the main.py file where you have your customer... bla bla respectively
- Run the main.py file
- Insert the data you want to analyze 
- Insert the number of tweets you wanna go over
- you're good


# some bugs you may get as beginner or if you just installed python to your system and probably didn't install it right
one of the bug for beginners could be your system not recognizing python or pip in the right path, that means you wouldn't be able to have tweepy working and some others
this would prompt errors
What you need do is to simply fix "python not recognized or pip not recognized" by adding the directory where you have the python.exe in the right path and also, doing the same for the pip 
(if this sounds complicated for you as a beginner)
Just google "how to fix python is not recognized" or "pip is not recognized" you know
Once you fix that, you should be good to go









# Twitter-Sentiment-Analysis

This script can tell you the sentiments of people regarding to any events happening in the world by analyzing tweets related to that event. It will search for tweets about any topic and analyze each tweet to see how positive or negative it's emotion is. You might want to check out this complete text and video based detailed [tutorial link](http://www.letscodepro.com/Twitter-Sentiment-Analysis/)

![alt text](http://www.letscodepro.com/wp-content/uploads/2017/09/TwitterSentimentAnalysis.png)


## Getting Started
 
First of all login from your Twitter account and goto [Twitter Apps](https://apps.twitter.com/). Create a new app ([How to create twitter app](http://www.letscodepro.com/twitter-sentiment-analysis/)) and goto __Keys and access tokens__ and copy Consumer Key, Consumer Secret, Access Token and Access Token Secret. We will need them later. 

### Installation

Download or Clone the repo, Navigate to the directory containing the files and run
```
python setup.py install
```
or if you have different versions of python installed then
```
python3 setup.py install 
```
to install the dependencies.


### Usage

Once you have created an app on twitter and installed all the dependencies by running __setup.py__, open main.py and paste your Consumer Key, Consumer Secret, Access Token and Access Token Secret. After that save and run the script. You will be prompted to enter the keyword/hashtag you want to analyze and the number of tweets you want to analyze. Once the analysis is completed, a pie chart will be generated disclosing the results of analysis.

## Built With

* Python 3.6
* tweepy
* textblob
* matplotlib

## Contributing

1. Fork it
2. Create your feature branch: git checkout -b my-new-feature
3. Commit your changes: git commit -am 'Add some feature'
4. Push to the branch: git push origin my-new-feature
5. Submit a pull request

## Authors

Muhammad Ali Zia

## License

This project is licensed under the MIT License - see the [LICENSE.md](https://github.com/the-javapocalypse/Twitter-Sentiment-Analysis/blob/master/License.txt) file for details

