# Electronic Voting Machine
This repo contains android and arduino code for EVM made during SHRISTI-2017 (Annual Techno-Hobby Exhibition). Connection between android app and arduino was established using HC-05 bluetooth module. 

## Features:
- Votes are stored in Arduino and are displayed in the app using "Fetch Result" button.
- "Enable vote" button is used to enable voting. After enabling, only first vote is counted and rest of the votes are ignored. Using same id twice is not allowed.
- "Reset" button can be used to set count of all votes to zero.
- "Start new election" lets one to start a fresh election. Enter number of candidates and their names to start a new election.

## To do:
- Add finger-print scanner
- Create a database in the app for storing candidate names and voter ids.
