# Catcharr
A tool to view Dispatcharr guides and remote scheduled recordings

***NOTE THIS TOOL IS 100% VIBE CODED GARBAGE - USE AT YOUR OWN RISK***

Prerequisites:

Dispatcharr configured, and an API account created with an API Key and an XC Password (not just a login password)

---------------------------------------------------------------------------------------------


How to use:

Download all the files and put them all in the same folder


---------------------------------------------------------------------------------------------

Edit index.html and locate the lines - and update them with your correct details - make sure you enter the XC password from dispatcharr

        const DIRECT_BACKEND_URL = 'http://192.168.1.1:9191'; 
        
        const API_KEY = 'YOUR_PERMANENT_API_KEY_HERE'; 
        const STREAM_USERNAME = 'YOUR_DISPATCHARR_USERNAME'; 
        const STREAM_PASSWORD = 'YOUR_DISPATCHARR_XC_PASSWORD'; 

---------------------------------------------------------------------------------------------

Edit default.conf and locate the line

proxy_pass http://192.168.1.1:9191/api/;

Replace the IP Address and port with those from your Dispatcharr instance

---------------------------------------------------------------------------------------------

Run Catcharr with the following command

docker compose up -d

---------------------------------------------------------------------------------------------

**The webpage should be connectable on port 8123**
