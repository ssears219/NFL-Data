# NFL-Data
Gathered data from various sources to combine NFL game data including game results, season statistics, and game weather information.

**Flat File:** nfl_games.csv (https://www.kaggle.com/toddwfloyd/footballscores/version/1#)  
**Description:** Tabular data representing each NFL game from 1920 to 2017.  
**Variables:**
1.	date (date)
2.	season (integer) - year
3.	neutral (binary) – denotes whether it was a neutral site
4.	playoff (binary) – denotes whether it was a playoff game
5.	team1 (string) – denotes home team
6.	team2 (string) – denotes away team
7.	elo1 (float) – rating for home team
8.	elo2 (float) – rating for away team
9.	score1 (integer) – score for home team
10.	score2 (integer) – score for away team
11.	result1 (float) – denotes whether home team won, 0.5 denotes tie

**Website Data:** https://www.pro-football-reference.com/years/  
**Description:** Adding the year on to the end of this url leads you to a page holding season statistics for each NFL season from 1920 to 2019, but I will go to 2017 (not including the 2017 season).  
**Variables to Scrape:**
1. year - season
2. team
3. wins
4. losses
5. ties
6. win loss perc - win loss percentage
7. points - points scored
8. points opp - points allowed
9. points diff - point differential
10. mov - margin of victory, (point differential / games played)
11. sos total - strength of schedule using Simple Rating System (SRS)
12. srs total - Team quality relative to average based on Simple Rating System, (srs = mov + sos = osrs + dsrs)
13. srs offense - Offense relative to average (osrs)
14. srs defense - Defense relative to average (dsrs)

**API Data:** https://rapidapi.com/awigmore/api/visual-crossing-weather  
**Description:** This api is able to return historical weather data for a specified period of time and City.  
**Variables:**  
1.	City
2.	Date
3.	Min Temperature
4.	Max Temperature
5.	Wind Speed
6.	Wind Gust
7.	Wind Direction
8.	Precipitation
9.	Precipitation Cover
10.	Snow Depth
11.	Visibility
12.	Weather Type  

