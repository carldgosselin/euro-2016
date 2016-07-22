# WORK IN PROGRESS...

# UDACITY - Machine Learning Engineer Nanodegree

# Capstone project - euro 2016

...

## Install

This project requires Python 2.7 with the pygame library installed:

https://www.pygame.org/wiki/GettingStarted

## Code

...

## Run

...

## Observations on team and player data

Data from uefa website:  http://www.uefa.com/uefaeuro/season=2016/statistics/

### Team-related data
* All team-related data had the exact same rows and columns.  
* The team-related data could be easily amalgamated into a single tab in an excel spreadsheet

### Player-related data
* On the other hand, the player-related data could not be easily amalgamated into a single
tab in a spreadsheet as the number of rows (players) varied from one measurement to another
* e.g. total number of players in tournament is 453 players
* e.g. some of the measurement excluded players who had "0" in all columns/measurements
* Action:  will need to manually input data into the master player_data spreadsheet

* Need to be mindful of duplication of name for different players such as Éder for Italy and Éder for portugal
* Action:  updated names as follows:  Éder (Italy) , Éder (Portugal)

* The data omitted players from a list when all measurements equaled "0".  I had to manually add the "0" values to the list
* Action:  cut and paste data to master list several times and then type in "0" values for missing player information.
... this was a very time consuming exercise.

### Goalkeeping-related data
* 4 teams out of 24 had two goalkeepers play in the tournament.  All other teams kept playing the same goalkeeper.
* This variation may pose a challenge for comparisons.

## Other Statistics

total matches played: 51	
total goals: 108	
goals per match: 2.12 	
average minutes per goal: 44

Timing of goals...
* 1 to 15 min: 	13
* 16 to 30 min: 	8
* 31 to 45: 		20
* 45+ min: 		1
* 46 to 60 min: 	21
* 61 to 75 min: 	15
* 76 to 90 min: 	19
* 90+ min: 		9
* 91 to 120 min:	2