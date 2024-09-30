# Comparison MLS Academy data with First team data between USA Players

## Introduction

This research aims to identify the key characteristics and behaviors of academy midfielders that contribute to their progression and eventual promotion to the first team. I aimed to compare the values between academy players and MLS midfielders and
strikers to identify which metrics stand out to earn a promotion to the first team.
Several U23 American players who developed in various U.S. academies and are now either playing in Europe or on the first team of an MLS club were selected for this comparison. 
`` player_stats.ipynb `` file contains different visualizations used for research and the final paper.


## Data

Using Wyscout, single player data was extracted as an .xlsx file (Excel), where each row representing a match the player participated in, spanning from academy teams to first teams and national teams.
The 2022-2023 MLS player data was obtained through a web scraping script in ``fbref_scraper.ipynb``, which extracted tables from the FBRef website.


## Requirements
- pandas
- requests
- matplotlib
- numpy
- soccerplots
