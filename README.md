This repository is destined to hold files in order to display some of the main Data Analytical skills developed by me, Gustavo Garofalo, in the past couple of years. 

Most of the skills displayed here were learned either by self studying or formal education, one of which is the Data Analytics and Visualization Bootcamp, an intensive 24 week program offered by the University of Central Florida (Cerificate awarded in March 2020).

Performing API calls is a phenomenal skill that allows Data Analysts to collect accurate, updated and remote data in real time. Although sometimes the API calls are charged, you can find several websites that provides them for free.

The skill displayed in this repository is API calls, using a Python program.

________________________________________________________________________________________________________________________________________
Description of the work done:
________________________________________________________________________________________________________________________________________

# Python API Homework - What's the Weather Like?

## Background

Whether financial, political, or social -- data's true power lies in its ability to answer questions definitively. So let's take what you've learned about Python requests, APIs, and JSON traversals to answer a fundamental question: "What's the weather like as we approach the equator?"

Now, we know what you may be thinking: _"Duh. It gets hotter..."_

But, if pressed, how would you **prove** it?

The solution was performed using a Python program, wrote in a jupyter notebook. In order for the code to work, one would have to retrieve their own API key from the website https://openweathermap.org/api; Retrieve the key and paste it in the file "api_key.py" found inside the "weather_api_call" folder. The data collected is stored by the program in the "ow_df.csv" file. The solution is graphed, the files are saved in a separed folder called "Charts", and the critical analysis written in "AOI trends.docx".

## WeatherPy

In this example, you'll be creating a Python script to visualize the weather of 500+ cities across the world of varying distance from the equator. To accomplish this, you'll be utilizing a [simple Python library](https://pypi.python.org/pypi/citipy), the [OpenWeatherMap API](https://openweathermap.org/api), and a little common sense to create a representative model of weather across world cities.

Your objective is to build a series of scatter plots to showcase the following relationships:

* Temperature (F) vs. Latitude
* Humidity (%) vs. Latitude
* Cloudiness (%) vs. Latitude
* Wind Speed (mph) vs. Latitude

Your final notebook must:

* Randomly select **at least** 500 unique (non-repeat) cities based on latitude and longitude.
* Perform a weather check on each of the cities using a series of successive API calls.
* Include a print log of each city as it's being processed with the city number and city name.
* Save both a CSV of all data retrieved and png images for each scatter plot.

### Copyright

Trilogy Education Services © 2019. All Rights Reserved.
