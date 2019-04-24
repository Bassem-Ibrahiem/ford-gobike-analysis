# Ford GoBike Analysis Project

Hi there folks! In a world of ever-changing options for transportation, it's evident that the traditional method of driving a car from point A to point B isn't the only thing we have to do anymore. This is evident with the growth of things like ride-sharing with Uber, scooter rentals with Lime, and of course, bicycle rental with Ford GoBike.

In this Udacity project, we'll be taking a look at some data provided to us by Ford's GoBike project. Ford has kindly made this data available to us [at this provided URL](https://www.fordgobike.com/system-data).

## Dataset

As already shared above, Ford kindly provided us with the data we'll need for this project. Because this data is always fluctuating, I downloaded to my laptop and uploaded to GitHub what I worked from as of April 24, 2019. This way, if you want to get the same results that I did, you can simply leverage the same data that I used!

Here are the fields provided to us within the primary source data sets. We won't necessarily be working with all of these, but it's still good to know what's in here.

```
 - Trip Duration (in seconds)
 - Start Time and Date
 - End Time and Date
 - Start Station ID
 - Start Station Name
 - Start Station Latitude
 - Start Station Longitude
 - End Station ID
 - End Station Name
 - End Station Latitude
 - End Station Longitude
 - Bike ID
 - User Type (Subscriber or Customer - "Subscriber" = Member or "Customer" = Casual)
 - Member Year of Birth
 - Member Gender
```

## Files Included

Here's a brief description of all the files at are available as part of this project.

 - **ford-gobike-trip-data**: This folder contains all the data we downloaded and then later assembled / cleaned for use in this project
 - **ford-gobike-exploration.ipynb**: This jupyter notebook is where we do all the exploration of the data to be used in our explanatory analysis and slides later.
 - **ford-gobike-explanation.ipynb**: This jupyter notebook synthesizes the information gleaned from the exploration notebook and will be the foundation for the slide deck down below.
  - **output_toggle.tpl**: Provided by Udacity and the good folks who built nbconvert, this hides the code in my slide deck built off the jupyter notebook above.
 - **ford-gobike-explanation.slides.html**: And finally, this is the slide deck that is built off the jupyter notebook above.

## Tech Stack

These are the following packages I used throughout this project.

```
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sb
import os
import requests
from io import BytesIO
from zipfile import ZipFile
```
