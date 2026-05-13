# Catcharr
A tool to view Dispatcharr guides and remote scheduled recordings

***NOTE THIS TOOL IS 100% VIBE CODED GARBAGE - USE AT YOUR OWN RISK***

Prerequisites:
Dispatcharr configures and an API account created with an API Key

How to use:
Download the docker-compose.yml and the index.html and put them both in the same location

Edit index.html and locate the line
const API_KEY = 'YOUR_PERMANENT_API_KEY_HERE'; // <-- Remember to put your key here!

Replace YOUR_PERMANENT_API_KEY_HERE with your API key from Dispatcharr

Run Catcharr with the following command
docker compose up -d
