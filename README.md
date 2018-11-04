# Web Scraping
This tool enables you to extract structured data from a website url [Read More](https://www.webharvy.com/articles/what-is-web-scraping.html)

###

# Usage
Run it on a terminal

Have `Python3` and `pip` installed

```shell
$ python3 -m venv <your_env>

$ source <your_env>/bin/activate

$ pip install -r dependencies.txt

$ python3
>>> from scraper import get_text
>>> for i in get_text(<your url>, <html element for example "p" or "li">):
...     print(i)
>>> Your text starts to print here ...
```

# Resources/ Credits
- https://realpython.com/python-web-scraping-practical-introduction/
- https://www.webharvy.com/articles/what-is-web-scraping.html
- https://realpython.com/web-scraping-and-crawling-with-scrapy-and-mongodb/


