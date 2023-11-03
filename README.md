# Project-Scraper
The following project is related to web scraping and storing information about the largest companies in the United States by revenue. This project provides a way to gather and store information about the companies. It is useful in the following areas:
-It allows market researchers to gather up to date data on the largest companies.
-It allowed businesses and investors to gain insight into market dynamics which is beneficial for identification of potential partnership opportunities.


# Main features of the project
-Web Scraping: The project utilizes the BeautifulSoup library to scrape data from a Wikipedia page. 

-Database Storage: The SQLAlchemy ORM is used to store the scraped data in a SQLite database. 

-Composite Key: The project demonstrates the use of a composite primary key in the Company model. 

-Data Retrieval and Display: The main.py module allows for the retrieval of the stored company data from the database. It calls the scraping function, fetches the company information, and displays it by printing the details of each company object.

# Libraries used for this project
BeautifulSoup: Used the BeautifulSoup library, specifically BeautifulSoup4 (bs4), for web scraping. 

SQLAlchemy: SQLAlchemy for Object-Relational Mapping (ORM) library allowing for interaction with databases using Python objects.

