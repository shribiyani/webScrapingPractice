# webScrapingPractice

## Web Scraping -
- Two ways to extract data from a website:
    1. **Through API** (if, exists)[ex. Facebook APi, Twitter API, Amazon API, etc.]
    2. **Web Scraping / Web Harvesting / Web Data Extraction**- means **accessing the HTML page of website** and **extracting useful / required information / data** from it.


- **STEPS** involved in scraping -
    1. **Send an HTTP request to the URL of website** - access to the particular website, result the server reponds to the request by returning HTML content of site.
        - requests package is used

    2. Parsing The Data - after getting accessed to the HTML content, we have to parse the data. Reason for it is -
        - HTML data is nested & we cannot extract required data
        - Create a Nested / Tree Structure of the HTML data.
        - **html5lib** most advanced pacakage for parsing

    3. Tree Traversal - navigating & searching the parse tree which created in Step 2.
        - BeautifulSoup - pulling data from HTML & XML files


#### Installing Required Libraries -
   - for BeautifulSoup - 
       - **!pip install bs4**
   - for Requests - 
       - **!pip install requests**
   - for HTML5LIB -
       - **!pip install html5lib**


In this Web Scraping Practice Tutorial, I scraped following - 
  1. an Review from Amazon.com, 
  2. an JobSearch from TimesJob.com,
  3. an Inspiration Quotes from passiton.com, Corey Schafer, and more, etc.



# Thanks for Visiting my Web_Scraping Practice Tutorial...
  5. Some youtube channels practice too like from - Cor
  


