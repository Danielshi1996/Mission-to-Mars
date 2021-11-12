# Mission-to-Mars

## Overview

Mission to mars project is a web scraping tool to excrat most recent Mars news, Mars fact, Mars featured image and hemisphere pictures from various external resources and store them in Mongo database. The scrapped data are presented by accessing HTML page which is rendered and hosted by using Flask.

## How to use
1. Set up mongo DB at back end.
2. Run app.py file to host the server.
3. Visit the page by entering local host URL.
4. When Scrape New Data button is clicked, external data are automatically scrapped and stored in mongo DB.
5. Web page will refresh and present the data scrapped.
