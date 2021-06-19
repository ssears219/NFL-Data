# NFL Game Data Cleaning and Merging

Gathered NFL game data from various sources and merged into one file that includes game results, season statistics, and game weather information.

## Description

What is the association between various NFL statistics like passing yards per game, yards allowed per game, etc. and game results? Is there an association between gametime weather and a strong rushing offense winning?
Is home feild advantage real? To answer these questions, you first need a complete dataset which includes NFL Team statistics for each year, weather data from each game, and game results. In this project I gathered data from
various sources and merged them into one complete NFL game data set.  

## Data Sources

* [NFL Game Data](https://www.kaggle.com/toddwfloyd/footballscores/version/1#) - A CSV file found on Kaggle containing game details and results.
* [Pro-Football-Reference](https://www.pro-football-reference.com/years/) - Website used to scrape team statistics data.
* [Weather API](https://rapidapi.com/awigmore/api/visual-crossing-weather) - An API I used to obtained weather data for each game.

## Contents

* Obtaining and Cleaning Data.ipynb - Notebook where I gathered data from all three sources and cleaned them.
* Merging Storing Visualizing NFL DataFrames.ipynb - Notebook where I merged all the data, stored the data in a database, and visualized some of the associations.
* NFL_Games_Stats_Wx_Data.db - Database containing final table
* NFL_Games_Stats_Wx_Data.xlsx - Excel file containing final table

## Tools
* Python
* Sqlite
* Sqlalchemy
* Matplotlib
* Plotnine
* BeautifulSoup

## Authors

Samuel Sears @ssears219

## Acknowledgments

* [Pro-Football-Reference](https://www.pro-football-reference.com/)
* [Toff Floyd's Kaggle Dataset](https://www.kaggle.com/toddwfloyd/footballscores/version/1#)
