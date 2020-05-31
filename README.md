# WEB-PROGRAM
$ pip install scrapy
$ mkdir brickset_scraper
$ cd brickset_scraper
import scrapy


class BrickSetSpider(scrapy.Spider):
    name = "brickset_spider"
    start_urls = ['http://brickset.com/sets/year-2016']
$ scrapy runspider scraper.py
