# python_web_scraping
Python web scraping project for winter break 2017

# Milestone 1:
Requests, Beautiful Soup and Pagination: Writing a simple script that that extracts quotes from http://quotes.toscrape.com/ and follows pagination links.  
Watch this excellent [tutorial](https://www.youtube.com/watch?v=vkA1cWN4DEc&list=PLZyvi_9gamL-EE3zQJbU5N3nzJcfNeFHU&index=1) that achieves the exact same functionality using a python library called scrapy. However for milestone 1, we will be using requests and BeautifulSoup4 libraries only. Brief tutorials for both are attached here:
* [Requests](https://www.youtube.com/watch?v=vkA1cWN4DEc&list=PLZyvi_9gamL-EE3zQJbU5N3nzJcfNeFHU&index=1)  
* [BeautifulSoup4](http://www.pythonforbeginners.com/python-on-the-web/beautifulsoup-4-python/) 

## Milestone 1 extension:
Some websites block requests with bad user agents. Check out http://mangafreak.com/robots.txt. All well made websites have a robots.txt that define request priviledges. Figure out if http://mangafreak.com is allowing your python scraper to access content and then fool the website to download one image (Hint: change headers). Use `urllib` or `urllib2` python library for this script. Here are some resources to begin with:  
* [urllib/urllib2](http://www.pythonforbeginners.com/python-on-the-web/how-to-use-urllib2-in-python/)  
* [robots.txt](https://varvy.com/robottxt.html)

# Milestone 2:
Use Scrapy library to download chapter-wise images from http://mangafreak.com. Use ImagePipelines and tweak settings to find best configurations to download images.
* [Scrapy documentation](https://doc.scrapy.org/en/latest/)

# Contributing
1. Fork this repo  
2. Make a new folder `python_web_scraping/yourname/` 
3. make a pull request and keep adding commits to it.  
4. pull requests will be merged after every milestone if they function properly.  
