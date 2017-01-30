## ![logo](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Getting Data: HTTP, APIs, and Webscraping

## Learning Objectives

At the end of this session, you will:
- Have a clear understanding of how APIs work, and why they are increasingly prevalent
- Know how HTTP protocol works
- Gain first hand experience using your very first API
- Learn the basics of webscraping
- Webscrape your first page
- Develop an exposure to various Python development tools (Spyder, Jupyter Notebooks)

## Lesson Materials

### Introduction

Our intro deck is in the assets folder.

### HTTP

Our discussion of how HTTP works is [here](/HTTP-protocol.md).

### Using Our First API!

Visit the API we'll be using here: www.omdbapi.com

The .py file (that we used in Spyder) to make requests and use our very first API (gasp!) is available [here](./code/api-usage-example.py)

### Scraping

We'll now discuss scraping.

Our first example page is [this](./code/example.html) page. We'll use [this](./code/webscraping.py) script in Spyder.

### Live Scraping

The moment we've (I've) been waiting for: live scraping.

http://www.opentable.com/washington-dc-restaurant-listings

Let's use [this](./code/webscraping-starter.ipynb) notebook. We're going to stop before the Selenium portion, given time constraints. I welcome you to complete the remainder of the notebook independently. :)

NOTE: when scraping websites, not all elements are static. We need a solution. We may not have time to cover headless browsers, but I will leave this Jupyter notebook available for you.


## Bonus

### Use Your Second API - the Department of Commerce API!

Use [this](https://github.com/josephofiowa/GA-DSI/blob/master/intro-to-apis-python/code/dept-of-commerce-example.py) .py file to work with the Dept of Commerce API!

For this part of the lesson, we're going to want to use a few tools:

- Be sure to [signup for your API key](https://api.data.gov/signup/)
- This is the [documentation for the Dept of Commerce API](https://www.commerce.gov/page/api-documentation-commercegov)
- Here's a list of [government API docs](https://api.data.gov/docs/)
- We're going to want to download this [handy extension Chrome extension](https://chrome.google.com/webstore/detail/json-formatter/bcjindcccaagfpapjjmafapmmgkkhgoa) and if you don't have Chrome, we'll use [this](http://jsonprettyprint.com/)


## Additional Resources

- General Assembly hosts a variety of workshops in Intro to Python for Data Analysis, Intermediate Python, part-time Data Science classes, and full-time Data Science Immersives. Check them out [here](https://generalassemb.ly/education/)
- Beginner [Jupyter Notebooks](https://github.com/jdwittenauer/ipython-notebooks) to learn more Python
- [Blog post on json with pandas](https://www.dataquest.io/blog/using-json-data-in-pandas/)
- [API article Wikipedia](https://en.wikipedia.org/wiki/Application_programming_interface)
- [Programmable web](http://www.programmableweb.com/)
- Please also download [Anaconda with Python 2.7 (not 3.5)](https://www.continuum.io/)
- A [discussion](https://medium.com/ggv-capital/a-tale-of-2-api-platforms-39f8dfd77436#.92bwnnahv) on APIs used properly for development (Slack) vs improperly (Twitter)