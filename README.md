# HTML_Challenge
# Mars Data Web Scraping and Analysis
# Overview
This project involves web scraping and data analysis to explore Mars-related data. It consists of two parts:

Scraping Mars News
Extract titles and preview text of the latest articles from the Mars News website.

Scraping and Analyzing Mars Weather Data
Extract and analyze a table of weather data from a Mars Temperature data webpage.

Project Structure
The project includes the following files and directories:

part_1_mars_news.ipynb: Jupyter Notebook for scraping Mars news titles and previews.
part_2_mars_weather.ipynb: Jupyter Notebook for scraping and analyzing Mars weather data.
mars_news.json (optional): JSON file storing scraped Mars news data.
mars_weather.csv: CSV file containing the cleaned Mars weather data.
# Instructions
Part 1: Scrape Mars News
Open part_1_mars_news.ipynb in Jupyter Notebook.
Use Splinter and BeautifulSoup to scrape the Mars News website (https://redplanetscience.com).
Extract the titles and preview text of articles.
Save the results as a list of dictionaries and optionally export them to mars_news.json.
Part 2: Scrape and Analyze Mars Weather Data
Open part_2_mars_weather.ipynb in Jupyter Notebook.
Use BeautifulSoup to scrape Mars weather data from the Mars Temperature Data site (https://static.bc-edx.com/data/web/mars_facts/temperature.html).
Convert the table data into a Pandas DataFrame and clean the data.
Perform the following analyses:
Determine the number of months on Mars.
Count the total number of Martian days in the dataset.
Identify the coldest and warmest months based on average minimum temperature.
Identify the months with the highest and lowest atmospheric pressure.
Estimate the length of a Martian year.
Export the cleaned data to mars_weather.csv.
# Dependencies
Ensure the following Python libraries are installed:

splinter
beautifulsoup4
pandas
matplotlib
jupyter
Install them using pip if necessary:
Results
Part 1: Mars News
A list of dictionaries containing article titles and previews is generated.
# How to Run
Clone this repository or download the files.
Open the notebooks in Jupyter:
bash
Copy code
jupyter notebook
Follow the instructions in each notebook cell to run the code.
Analyze the outputs and generated files.
