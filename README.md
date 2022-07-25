# Valorant Stats

Riot Games presents VALORANT: a 5v5 character-based tactical FPS where precise gunplay meets unique agent abilities. With over 14 million active monthly users, Valorant is one of the most popular (and free!) games out right now. In this project, I pull data from https://blitz.gg/


# Files

* ```valorant.py``` - Primary file which is run to scrape the data. This python script uses selenium to extract data (element from xpath) from the website.
* ```auto.bat``` - File for pushing the entire folder to the github repo. Pairs up with Windows Task Scheduler to push the data every X amount of days.

# Folders (Data)

* ```abilities_data``` - Folder of agent abilities usage. Includes data from the aggregate of all maps.
* ```agents_data``` - Folder of essential agent data, such as pick rate, win rate, and average combat score.
* ```map_data``` - Folder of essential map data, such as pick rate, win percentage for either side, and number of matches.
* ```weapons_data``` - Folder of essential weapon data, such as headshot percentage and average damage per round.
