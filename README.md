# b9122_homework2

## Author Information
<b>Author Name</b>: Yan Yu

<b>Author Email</b>: yan.yu@columbia.edu


## Description of the first code file (webcrawler.py)

This file contains a webcrawlers that can crawl seed url ("https://www8.gsb.columbia.edu") and collect pages that contain 10 child URLs.
At the end, the code will output number of URLs seen, number of URLs scanned and List of seen URLs.


## Description of the second code file (b9122_hw2_sol_Yan_Yu.ipynb)

This file contains two webcrawlers that can perform following tasks correspondingly:

1. Crawl pages whose seed url is the press releases page of the Federal Reserve System: https://www.federalreserve.gov/newsevents/pressreleases.htm and collect pages that contain the word “covid” found within the page. The goal is to collect at least 10 such urls. 
At the end of the crawling the code should output the urls of the webpages found to contain the word “covid”. When checking whether the word is present on the webpage, the webcrawler will consider lower- and upper-case word versions (Covid, COVID, covid). 

2. Crawl pages whose seed url is the press releases page of the Securities and Exchange Commission: https://www.sec.gov/news/pressreleases and collect urls of press releases that contain the word “charges”. The code should output the first 20 such links that it finds. 
For each link, the webcrawler will output the url and the text. When checking whether the word is present on the webpage, the webcrawler will consider lower- and upper-case word versions. 
