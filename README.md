# Mission-to-Mars
Build an App to scrape websites for data pertaining to the Mission to Mars, and then create an HTML page to display findings.

## Overview
Junior Dataa Analyst Robin does freelancing astronomy work in her free time. Her dream is to land a position with NASA one day so she spends a lot of time visiting sites with news about space exploration, especially about Mission to Mars. Robin decides to write a script that would gather all the information she searches for into one convienient central location without spending here free time gathering the data manually and share the information with others.

## Summary 
A webpage application was created to scrape the new data with a click of a button. Robin had to learn how web pages work so that she was able to write a python script that can navigate the web pages and collect the right information. After gathering all data she had to store the data using a No SQL database MongoDB because data pulled from the internet comes in different formats it is not always a neat and tidy table that SQL requires. To put it all together in a web application she used Flask and bootstrap for extra polish.

## Challenge Overview
Robin's web app is looking good and functioning well, but she wanted to add more polish to it. She had been admiring images of Mars’s hemispheres online and realized that the site is scraping-friendly. 
She wanted to adjust the current web app to include all four of the hemisphere images. To do this, we had to use BeautifulSoup and Splinter to scrape full-resolution images of Mars’s hemispheres and the titles of those images, store the scraped data on a Mongo database, use a web application to display the data, and alter the design of the web app to accommodate these images.


![image](https://user-images.githubusercontent.com/78935551/117555459-5ae66e80-b02d-11eb-8914-23fd89cea85a.png)


