# Data-Collection-Challenge
UTSA Data Analytics Bootcamp data visualization challenge where data from a Mars HTML page will be scraped and parsed using Splinter and BeautifulSoup and then analyzed via the pandas python library.

------------------------------------------------------------------------------------------------------------------
MARSDATASCRAPE

The Data-Collection-Challenge repository contains one primary folder called MarsDataScrape, which contains the part_1_mars_news.ipynb and part_2_mars_weather.ipynb files, as well as the data_output folder which contains the mars_weather.csv file.

------------------------------------------------------------------------------------------------------------------
part_1_mars_news.ipynb

The part_1_mars_news.ipynb file uses Splinter chrome web browser along with BeautifulSoup in order to parse and scrape html data from the Mars news webpage. The text of the page is all extracted and isolated and then iterated through in order to provide a dictionary output of all article titles and article preview texts as key-value pairs.

------------------------------------------------------------------------------------------------------------------
part_2_mars_weather.ipynb

The part_2_mars_weather.ipynb file again uses Splinter chrome web browser with BeautifulSoup to this time visit the Mars weather data table webpage and scrape the html data from the table. The data rows are then iterated through and stored into lists that are processed into a pandas dataframe for data storage. The dataframe is then used for analysis and data visualization to answer questions regarding time and weather data on Mars. After completion of analysis, the file will then export the dataframe to the data_output folder as the mars_weather.csv file.