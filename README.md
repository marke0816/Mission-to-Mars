# Mission-to-Mars

This repository uses Flask, MongoDB, and BeautifulSoup to scrape news data from NASA's Mars missions and satellite imagery.

The app.py file creates a Flask webapp using the webscraping functions defined in the scrapying.py file.  The data is stored in a mongo database (noSQL).

The app scrapes the latest news title, a brief description of the article, the newest featured image, and a table of comparison data between Earth and Mars.