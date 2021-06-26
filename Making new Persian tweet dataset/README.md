# Scraping Persian Tweets to make a new Persian Dataset
The tweets have been pulled from Twitter using `snscrape`and manual tagging has been done based on Ekman's 6 main emotions.
For privacy sake, I pre-process and remove usernames, display names, and mentions from all tweets. Also, I deleted the timestamps and Tweets IDs.

Columns:
1) tweet
2) replyCount
3) retweetCount
4) likeCount
5) quoteCount
6) hashtags
7) sourceLabel
8) emotion

Please leave an upvote if you find this relevant. P.S. I am new and it will help immensely. :)

# snscrape
snscrape is a scraper for social networking services (SNS). It scrapes things like user profiles, hashtags, or searches and returns the discovered items, e.g. the relevant posts.

The following services are currently supported:

* Facebook: user profiles, groups, and communities (aka visitor posts)
* Instagram: user profiles, hashtags, and locations
* Reddit: users, subreddits, and searches (via Pushshift)
* Telegram: channels
* Twitter: users, user profiles, hashtags, searches, threads, and list posts
* VKontakte: user profiles
* Weibo (Sina Weibo): user profiles

**Please note that some features listed here may only be available in the current development version of snscrape.**

## Requirements
snscrape requires Python 3.8 or higher. The Python package dependencies are installed automatically when you install snscrape.

Note that one of the dependencies, lxml, also requires libxml2 and libxslt to be installed.

## Installation
    pip3 install snscrape

If you want to use the development version:

    pip3 install git+https://github.com/JustAnotherArchivist/snscrape.git