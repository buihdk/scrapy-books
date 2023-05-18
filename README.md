This python tool is used to crawl book data from the website https://books.toscrape.com 

## Steps to crawl
- run `python -m venv venv` at root to create a virtual environment
- run `source venv/bin/activate` at root to activate the newly created virtual environment
- run `pip install -r requirements.txt` to install all the required modules for this python project
- run `scrapy crawl bookspider` inside web-scrapy/bookscraper/bookscraper to start crawling
### A few useful commands
- run `scrapy startproject bookscraper` inside web-scrapy to initiate a bookscraper project
- run `scrapy genspider bookspider books.toscrape.com` inside bookscraper/spiders to generate a spider bookspider
- run `pip3 install ipython`
- add `shell = ipython` in scrapy.cfg
- run `scrapy shell` for testing scrapy commands
- run `scrapy crawl bookspider -o bookdata.csv` to craw and output data to bookdata.csv 
- run `scrapy crawl bookspider -o bookdata.json` to craw and output data to bookdata.json 
