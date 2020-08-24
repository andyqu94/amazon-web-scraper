# amazon-web-scraper
This project is composed of webscraping from amazon.ca and performing ETL on the scraped data

## Procedure taken
1. Importing webdriver to navigate to the page that user wants to scrape
2. Generate a list containing all relevent information of the products that is on the webpage
3. Clean and sort the list according to what information is needed and generate a data frame from the list
4. Connect to mysql database and use pandas to create and insert the data that came from the data frame. 
