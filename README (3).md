
# 👯‍♀️Keeping Up With Trends ⚡️
# Trend Extraction from Social Media Data




## 🧠 Problem Statement in Flipkart Grid 4.0
Problem Definition: Extract Trends from social media data As part of this challenge, teams are expected to identify trends from social media data; From all the products available on Flipkart identify trending products, utilize all signals available (ex. posts, sessions, check-ins, social graphs, media content, etc.). Output should also have photos, videos, gifs which can be used on Flipkart app.Preferred tech: Open source Bonus: Signal extraction from multiple social media channels (ex. Pinterest, Instagram etc.)

## 👩‍💻 What we did in this project? 
Extracted data from various Fashion Blogs and social media using BeautifulSoup and AutoScraper.
Identified fashion trends by structuring data with Pandas and Python, created a mapping of trending keywords
with Flipkart product categories and generated searchable terms.
Selenium was used for real-time image extraction from Instagram corresponding to relevant keywords.

## 🚀 Brief Approach
Scrape data from Pinterest, Zara, Amazon, Instagram, etc.
Extract trends from the data
Output the trends in a format that can be used on Flipkart app

## 🛠 Tech Stack
    1. Python 3.6
    2. Selenium2
    3. BeautifulSoup4
    4. Pandas
    5. AutoScrapper


## 🤔 REQUIREMENTS: 
STEP1 - Clone the repository in your device using git clone or you can simply download the code file from this github repository.

STEP2 - Install Chrome Driver from https://chromedriver.chromium.org/downloads in your device and record the path of the chromedriver.exe file.

STEP3 - Open the code files in your own Virtual Environment or you can also use pyCharm as the IDE for an inbuilt virtual enviroment to run your code files.

STEP4 - Copy and Paste the path of the chrome driver in the path variable in main.py file (line 97)

STEP5 - Install the following libraries in your Virtual Environment using the code below
## Installation
Install Dependencies
```bash
  $ pip install beautifulsoup4
  $ pip install selenium
  $ pip install pandas
  $ pip install autoscraper
  $ pip install requests
  $ pip install os
```

Install Chrome WebDriver
```bash
  https://chromedriver.chromium.org/downloads

```
    
## 👯‍♀️Contents
| Folder | contents |
| :-----: | :---: | 
| main.ipynb | structured data,Discovered Trending keywords, and created mapping  | 
| insta.ipynb | Extracts images from Instagram | 
| pinterest | Scrapes data from Pinterest  | 
| zfashion-blogs | Extrats data from varios fashion blogs | 
| clothingstore | Trending products info fron Zara, Amazon  | 
| widelegjeans | A Demo of images extracted from Instagram for keyword #widelegjeans | 

## License

This project is released under a free and open-source software license, [MIT License](https://choosealicense.com/licenses/mit/)

