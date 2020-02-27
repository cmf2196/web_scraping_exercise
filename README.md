Project: Data Pipeline and Web Scraping <dir>
Author: Connor Finn <dir>
Data: February 27, 2020 <dir>
 <dir>

## Project Description
This repo is an exercise I completed for my Data Science course which involves created a data pipeline, and scraping a webpage for some 'interesting' data. The [webpage](https://www.cntraveler.com/gallery/best-restaurants-in-new-york-city) I chose to scrape is a blog style webpage which described some of the top restauraunts in NYC. The file is saved to csv as indicated by the created data pipeline class. 

## Files included: <dir>
  * web_scraper.ipynb
  * ./data/restaurant_data.csv
    + note that the file is saved in the data repositor
 
## Running Instructions
  Simply run the jupyter notebook file. If a data repo does not exist, the script will create the folder and the csv file. 
  
## Additional Notes
  * This project uses the beautifulsoup package, along with requests and lxml.html to scrape and parse the webpage.
  * Pandas is used to organize the data and eventually write to csv.


