# RIAWebScraper
This scraper relies on keyword and date parameters to scrape title, metadata, and text from RIA Novosti articles.

The function, scrapeRIA, takes keyword (string) in English or Russian, four digit startYear, four digit endYear, one or two digit startMonth, and one or two digit endMonth (all int). It returns the data as a .txt file. 
When importing this file into Excel, select UTF 8 and * as the delim.
