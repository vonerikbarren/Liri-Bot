# Liri-Bot

# Assignment 8: Liri-Bot

## Overview / Description
- LIRI is like iPhone's SIRI. However, while SIRI is a Speech Interpretation and Recognition Interface, LIRI is a Language Interpretation and Recognition Interface. LIRI will be a command line node app that takes in parameters and gives you back data.


## Pseudocode
1. First create initialize a git repository with README.md
2. clone it to computer
3. move to directory via bash
4. bash: npm init -y to create package.json
5. bash: touch .gitignore
6. bash: touch keys.js
7. code: begin writing program by running console.logs for API credentials for twitter & spotify
8. web: Create accounts with websites to obtain API access & API keys
9. code: Once accesscodes and API keys are obtained, create a random.txt file and add some text to be read by LIRI
10. bash: touch liri.js 
11. code: liri.js: write code needed to grab data from keys.js and store them within a variable
12. code: liri.js: create code so that liri can run the commands:
    1.  look-at-my-tweets
        1.  this will display 20 tweets from my twitter account
    2.  spotify-this-song
        1.  this will show an artist, song name, preview link to spotify, and album name
    3.  movie-this
        1.  this will show title, year, IMDB rating, Rotten Tomatoes %, Country, Language, Plot, and actors
    4.  do-it-now
        1.  read the contents of a .txt file 
