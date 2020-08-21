# Weather-Journal App Project

## Overview
Asynchronous web app that takes in a user's zip code and entered thoughts.  It uses an API to post the current weather in their area in conjunction with their text entry to dynamically update the UI, creating a journal entry.

## Specifics
Server created and Express, Body-Parser, and Cors packages installed

GET and POST routes return and add project data

API credentials acquired from openweathermap.org

Async GET request to the API retrieves desired data, POST request is chained to add desired API data and user data to the app

Another promise is chained which updates the UI dynamically with information for temperature, date, and user input
