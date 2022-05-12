# KnowledgeGraph-NLP
Building a knowledge graph from the text scrapped from https://english.onlinekhabar.com/ articles

Scrape text data from some selected articles from above link.

HTML web scrapping using BeautifulSoup(!pip3 install bs4) python library.

In order to work with the HTML, we will have to get the HTML as a string. We can easily get HTML data by using get() function in requests module(!pip3 install requests).

Once the HTML is fetched using requests the next step will be to parse the HTML content.


Save Scraped Text Data to CSV File and then Read CSV File.

Data Cleaning:In this stage we have to remove all the insignificant words in the observation such as stop words(eg. etc).In this case there is a library provided by nltk (natural language tool kit).


Build a Knowledge Graph from Text Data.
