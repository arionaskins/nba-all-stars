# NBA-ALL-STARS <br>
### Arion Askins, Luis Alfaro, & Faraz Hafeez

---------------------------------------------------------------

## Project Proposal<br>

### Project Goal & Motivation <br>
Sports have been one of the greatest American pastime, but there is also constant debate among people about who the greatest athletes are. With the impressive NBA season last year in the ‘Bubble’ and an aging group of all-stars that will retire within the next five years our group decided to find out the statistical data behind all the NBA players since the 1976 merger of the ABA till 2020. We want to compare historical NBA data based on teams and players with modern NBA data to gain and compare performance insights based on factors such as win rate, in the regular and off-season, and performance values. Doing so will allow us to provide concrete statistics comparing older players, mainly all-stars, with newer ones which will help the debate for who the greatest players in the NBA are. 
<br>

### Data Description <br>
The dataset chosen was derived from an article FiveThirtyEight displaying data on reported NBA players. The overall data is composed of four datasets:
<center>`
* modern_RAPTOR_by_team.csv
* modern_RAPTOR_by_player.csv
* historical_RAPTOR_by_player.csv
* historical_RAPTOR_by_team.csv`
</center>
These are the primary datasets we will be working with and they contain data on NBA players from as early as 1976 up until around 2015. The source also includes links to two additional datasets, `latest_RAPTOR_by_player.csv` and `latest_RAPTOR_by_team.csv`, which both include data on all breakout players for the latest year, 2021. <br>
The datasets chosen are composed of around 28,000 rows and around 16 columns, given each dataset has different quantities of features/entries. Some of the variables included within the data sets: player_name,a string containing the player name; season,an int type of the year reported;  season_type, a nominal variable of whether it was a regular season or during playoffs; mp an int of how long the player was actively playing, in seconds.
<br>

### Data Analytic Steps / Techniques <br>
In order to begin using the data, we will need to retrieve it from the FiveThirtyEight website. The website links to a GitHub repository with the data mentioned above as CSV files. After importing it into python using the pandas library, we will be able to get information about the data; this includes the number of rows, the number of columns, and glimpses of the data so we know how to approach it. <br>
One basic step we will take to clean and get the data ready for use is removing any duplicate and unnecessary data. Some files have up to 28,000 rows so cleaning that up at the start will make our workspace cleaner and our code more efficient. We will also need to familiarize ourselves with the data in order to use and manipulate it. This can include viewing graphs of the data, using the describe() function to get summaries of specific columns, and getting the data type of each variable. The data has not been used yet but this preparation will prove very useful once we begin using it. <br>
An advanced technique learned in class is concatenating which will be put to use for this project. Not all files have the same columns which is why we might have to remove some data. Once we clean and remove extra data, we will be able to concatenate the data frames into one to compare them more easily. From then, we can use aggregate and graph functions to display, compare, group, and understand the data more clearly to achieve our goal. <br>
For this project, we will not need to scrape any data from a website. All the data we need were put into CSV files beforehand and we are able to download them and put them into a pandas data frame. <br>

[Link to the original datasets](https://github.com/fivethirtyeight/data/tree/master/nba-raptor)
[Our current version of the dataset](https://docs.google.com/spreadsheets/d/1vJCiUG7K_vsxXSn9VkqHklY9X73OGxxoi45pk9GyeEM/edit?usp=sharing)
