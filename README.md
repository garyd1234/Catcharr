# Catcharr
A tool to view Dispatcharr guides and remote scheduled recordings

***NOTE THIS TOOL IS 100% VIBE CODED GARBAGE - USE AT YOUR OWN RISK***

Prerequisites:

Dispatcharr configured, and an API account created with an API Key

---------------------------------------------------------------------------------------------


How to use:

Download the docker-compose.yml, default.conf and the index.html and put them all in the same folder


---------------------------------------------------------------------------------------------

Edit index.html and locate the line

const API_KEY = 'YOUR_PERMANENT_API_KEY_HERE'; // <-- Remember to put your key here!

Replace YOUR_PERMANENT_API_KEY_HERE with your API key from Dispatcharr

---------------------------------------------------------------------------------------------

Edit default.conf and locate the line

proxy_pass http://192.168.1.1:9191/api/;

Replace the IP Address and port with those from your Dispatcharr instance

---------------------------------------------------------------------------------------------

Run Catcharr with the following command

docker compose up -d
