# usproxy-scrapy
this script uses scrapy framework to scrape categories and each category's tuturials from tutsplus.com using the CrawlSpider template

# messures used to avoid detection

Using a custom user-agent rotator calss and Setting AUTOTHROTTLE_ENABLED = True


# Installation

```bash
pip install scrapy
```
## Usage

```
scrapy crawl tutsplus -o filename.json or filename.csv
```
