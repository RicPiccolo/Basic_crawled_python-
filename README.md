# Basic_crawler_python-
Just a basic crawler which will help you collect data {Mostly for QA needs}

Changes (Recursion added. It will help to crawl all site pages - if you don't want to use it - delete file spiderman-recursive by path  Basic_crawled_python-/basic_crawler/basic_crawler/spiders/)

How to use

First things first

1.Instal scrapy with {pip install scrapy}

2. Fork this repo and go to main directory basic_crawler

3. Run {scrapy crawl basic_crawler -o books.json -t json} - script should return all titles of books from related site and put it into books.json

4. Open file with {vi books.json}

This is just basic crawler which will help to collect required info
Enjoy it - you can simply choose element to crawl - just set it in items.py
