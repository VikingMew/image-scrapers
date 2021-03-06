# image-scrapers

[![Build Status](https://travis-ci.org/rushilsrivastava/image-scrapers.svg?branch=master)](https://travis-ci.org/rushilsrivastava/image-scrapers)

Image Scrapers built for scraping/downloading Bing and Google images + metadata. Both the Bing and Google Scraper work in Python 2 and 3. You can use these scripts to download images that Bing and Google return in search queries.

Both the scrapers will save to their own folders under a global folder called `dataset`.

## How to Use

### Google Image Scraper/Downloader:

Make sure you install the requirements by doing:

    pip install -r requirements.txt

Ensure you have the [appropriate version](https://sites.google.com/a/chromium.org/chromedriver/downloads) of ChromeDriver on your machine.

Then:

    python google_scraper.py cats

### Bing Image Scraper/Downloader:

#### Without API Key:

Make sure you install the requirements by doing:

    pip install -r requirements.txt

Then:

    python bing_scraper.py cats


#### With API Key:

Get a [Bing Image Search API Key](https://azure.microsoft.com/en-us/services/cognitive-services/bing-image-search-api/).

Make sure you install the requirements by doing:

    pip install -r requirements.txt

Then:

    python3.5 bing_scraper_key.py cats -key YOUR_API_KEY_HERE


## FAQs

*How can I download a specific amount of images?*
 - Use the `--limit` flag to define the amount of images you want to download. 

*How do I search with custom filters on Google Images?*
 - Use the `--url` flag to define your own url with the search filter.

## Disclaimer

This program lets you scrape/download many images from Bing and Google. Please do not download any image violating its copyright terms. Google Images and Bing Images are merely search engines that index images and allow you to find them. Neither Google nor Bing produce these images, and as such, they don't warrant a copyright on any of the images. The original creators of the images own the copyrights.

Images published in the United States are automatically copyrighted by their owners, even if they do not explicitly carry a copyright warning. You may not reproduce copyright images without their owner's permission, except in "fair use" cases. You could risk running into lawyer's warnings, cease-and-desist letters, and copyright suits. Please be careful, and make sure your are not violating any laws!
