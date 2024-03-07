# Description

The primary tool utilized for web scraping was Beautiful Soup2, a Python library renowned for its ability to pull data out of HTML and XML files. 
It provides simple methods for navigating, searching, and modifying the parse tree, making it an ideal tool for the task. 
Together with the requests3 library, which was used to make HTTP requests to the review pages, these tools formed the foundation of the data scraping architecture.

The script was designed to go through the pages of the review website one after the other accessing and collecting data, 
also adhering to the robots.txt files by maintaining a reasonable request rate to avoid overwhelming the websites server and periodically refreshing sessions to prevent detection of non-human activity. 
These measures allowed for the collection of a dataset while upholding ethical scraping standards.
The collected data includes metrics essential for sentiment analysis such as review titles, dates, ratings, and the actual reviews themselves.
