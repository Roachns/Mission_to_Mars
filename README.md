# Mission_to_Mars

Introduction

The purpose of this project is to build a web application that scrapes various websites for data related to the Mission to Mars and displays the information in a single HTML page. Scraping was completed via the python library Beautiful Soup.

## Step 1 - Scraping
Complete your initial scraping using Jupyter Notebook, BeautifulSoup, Pandas, and Requests/Splinter.
- Create a Jupyter Notebook file called `mission_to_mars.ipynb` and use this to complete all of your scraping and analysis tasks. The following outlines what you need to scrape.

## NASA Mars News
Scrape the NASA Mars News Site and collect the latest News Title and Paragragh Text. Assign the text to variables that you can reference later.

```
Example: 
news_title = "NASA's Next Mars Mission to Investigate Interior of Red Planet"

new_p = "Preparation of NASA's next spacecraft to Mars, InSight, has ramped up this summer, on course for launch next May from Vandenberg Air Force Base in central California -- the first interplanetary launch"
```
## JPL Mars Space Images - Featured Image
- Visit the url for JPL's Featured Space Image [here](https://www.jpl.nasa.gov/spaceimages/?search=&category=Mars)
- Use splinter to navigate the site and find the image url for the current Featured Mars Image and assign the url string to a variable called `featured_image_url`.
- Make sure to find the image url to the full size `.jpg` image.
- Make sure to save a complete url string for this image.

```
Example:
featured_image_url = 'https://www.jpl.nasa.gov/spaceimages/images/largesize/PIA16225_hires.jpg'
```

## Mars Weather
