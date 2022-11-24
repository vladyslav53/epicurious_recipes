# Epicurious Recipes

## Description
- A Web Scraping project that crawls over **2000 pages** and scrapes over **36000 unique recipes** from the [Epicurious](https://www.epicurious.com/) website
- The data is scraped using **Asynchronous HTTP Requests** in Python with `aiohttp` and `asyncio`
- For comparing **speed**, the data is also scraped using **Synchronous HTTP Requests** in Python with `requests`

## Project Contents
- [asynchronous_recipes_scraper.py](https://github.com/sagar-0817/epicurious_recipes/blob/main/asynchronous_recipes_scraper.py)
    - the python script scrapes recipes from the Epicurious website **asynchronously**
- [synchronous_recipes_scraper.py](https://github.com/sagar-0817/epicurious_recipes/blob/main/synchronous_recipes_scraper.py)
    - the python script scrapes recipes from the Epicurious website **synchronously/sequentially**
- [requirements.txt](https://github.com/sagar-0817/epicurious_recipes/blob/main/requirements.txt)
   - contains the packages required to run the script(s)
- [.github/workflows/python-script-execute.yaml](https://github.com/sagar-0817/epicurious_recipes/blob/main/.github/workflows/python-script-execute.yaml)
    - a manually triggered workflow to run any of the asynchronous/synchronous recipes scraper based on the user input
    