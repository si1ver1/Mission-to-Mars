
# Mission to Mars

## Overview of Project
The goal of this assignment is scrape web data from various different mars related website. The data is stored into a Mongo DB and the stored data is displayed in a website built around Flask.

### Results of Mission to Mars
Below we can see the view of the website:

![full_page](https://github.com/si1ver1/Mission-to-Mars/blob/master/data/full_page.png?raw=true) 

Some features on the page:
* Hitting scrape data goes through the entire scraping process and returns a success when done.
* The first section scrapes the title and description of the first article on https://mars.nasa.gov/news/
* The second section on the left pulls the main image at the moment on https://www.jpl.nasa.gov/spaceimages/?search=&category=Mars
* The secod section on the right pulls the chart from http://space-facts.com/mars/
* The third section pulls 4 different images and their associated titles from https://astrogeology.usgs.gov/search/results?q=hemisphere+enhanced&k1=target&v1=Mars

The final setup was to use the bootstrap settings. We setup the 4 mars images at the bottom to be in a table that automatically expands and condenses according to the users window. We also set them to display as icons and added proper spacing.

### Summary
We successfully scrapped data from various sources and displayed it in an organized webpage that automatically adjusts according to screen size. Scraping the data uses try/catch methods to check for errors. As long as the success code returns we know our scraping is still successful and does not need to be updated.