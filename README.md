# data_scraping_project
The main objective of this project is to deploy a web API to serve news data with filtering parameters date, tags, and limit. Firstly, I developed code to scrape data from a news website and store them as dictionaries in the MongoDB database. Subsequently, I deployed my code to Heroku and set a scheduler to run the scraping hourly. Finally, I developed and deployed a flask API to Heroku, which allows people to request news data from my database.