# **WebScraping**
## **Introduction**
### **What is Web Scraping?**
Web scraping is the process of collecting and parsing raw data from the Web, and the Python community has come up with some pretty powerful web scraping tools.

The Internet hosts perhaps the greatest source of information on the planet. Many disciplines, such as data science, business intelligence, and investigative reporting, can benefit enormously from collecting and analyzing data from websites.

### **Scrape and Parse Text From Websites**
Collecting data from websites using an automated process is known as web scraping. Some websites explicitly forbid users from scraping their data with automated tools like the ones that you’ll create in this tutorial. Websites do this for two possible reasons:

1. The site has a good reason to protect its data. For instance, Google Maps doesn’t let you request too many results too quickly.<br>
2. Making many repeated requests to a website’s server may use up bandwidth, slowing down the website for other users and potentially overloading the server such that the website stops responding entirely.<br>

Before using your Python skills for web scraping, you should always check your target website’s acceptable use policy to see if accessing the website with automated tools is a violation of its terms of use. Legally, web scraping against the wishes of a website is very much a gray area.

## **Use an HTML Parser for Web Scraping in Python**
There are many Python tools written for this purpose, but the Beautiful Soup library is a good one to start with.<br>
### Install Beautiful Soup
```bash
 $ python -m pip install beautifulsoup4
```
With this command, you’re installing the latest version of Beautiful Soup into your global Python environment.  
