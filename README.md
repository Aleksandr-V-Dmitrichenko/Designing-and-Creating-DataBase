# Designing-and-Creating-DataBase
In this project I designed and created database. As a basis was taken several tables which contains data about [Major League Baseball](https://en.wikipedia.org/wiki/Major_League_Baseball) games from [Retrosheet](https://www.retrosheet.org). 
This sheet compiles detailed statistics on baseball games from the 1800s through to today. The main file game_log.csv has been produced by combining 127 separate CSV files from retrosheet, and has been pre-cleaned to remove some inconsistencies.
The game log has hundreds of data points on each game which I normalized into several separate tables using SQL, providing a robust database of game-level statistics.

In addition to the main file, I have also included three 'helper' files, also sourced from Retrosheet:

* park_codes.csv
* person_codes.csv
* team_codes.csv
* appearance_type.csv

There is a game_log_fields.txt file from Retrosheet which explains the fields included in the main file.
