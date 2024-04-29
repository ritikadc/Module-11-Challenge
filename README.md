# module-11-challenge
Mars Data - Web Scraping

# Instructions

## Part 1: Scrape Titles and Preview Text from Mars News
- Open the Jupyter Notebook in the starter code folder named part_1_mars_news.ipynb. You will work in this code as you follow the steps below to scrape the Mars News website.
- Use automated browsing to visit the Mars news site Links to an external site.. Inspect the page to identify which elements to scrape.
- Create a Beautiful Soup object and use it to extract text elements from the website.
- Extract the titles and preview text of the news articles that you scraped. Store the scraping results in Python data structures as follows:
-  Store each title-and-preview pair in a Python dictionary and, give each dictionary two keys: title and preview. An example is the following:
-  ![image](https://github.com/BrennanB572/module-11-challenge/assets/114636599/3b9b8991-b38f-4531-95b8-f536050570ec)
-  Store all the dictionaries in a Python list.
-  Print the list in your notebook.
-  Optionally, store the scraped data in a file (to ease sharing the data with others). To do so, export the scraped data to a JSON file. (Note: there will be no extra points for completing this.)

## Part 2: Scrape and Analyze Mars Weather Data
- Open the Jupyter Notebook in the starter code folder named part_2_mars_weather.ipynb. You will work in this code as you follow the steps below to scrape and analyze Mars weather data.
-  Use automated browsing to visit the Mars Temperature Data Site Links to an external site.. Inspect the page to identify which elements to scrape. Note that the URL is https://static.bc-edx.com/data/web/mars_facts/temperature.html.
-  Create a Beautiful Soup object and use it to scrape the data in the HTML table. Note that this can also be achieved by using the Pandas read_html function. However, use Beautiful Soup here to continue sharpening your web scraping skills.
-  Assemble the scraped data into a Pandas DataFrame. The columns should have the same headings as the table on the website. Here’s an explanation of the column headings:
-  ![image](https://github.com/BrennanB572/module-11-challenge/assets/114636599/f1342413-6d68-4ce5-9f9d-acb5b6f40fd0)
-  Examine the data types that are currently associated with each column. If necessary, cast (or convert) the data to the appropriate datetime, int, or float data types.
-  Analyze your dataset by using Pandas functions to answer the following questions:
-  ![image](https://github.com/BrennanB572/module-11-challenge/assets/114636599/babc288a-1bf2-430f-8831-0ac3c3ac0fdd)
-  Export the DataFrame to a CSV file.
