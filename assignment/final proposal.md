# Final Project Proposal

Your assignment this week is to write a detailed proposal for your final
project. In proposing your final, try to address each of the following
areas.


## Problem / Question


When someone wants to move to and live in Philly, whether they want to rent or buy an apartment or house, they usually take the school, renting/sell price, hospital,crime rate and transportation information into consideration. The application can help users with all these problem. There will be two ways to use the application, first you can pick the location on the map or according to the zip code, the application will help you evaluation the living qualities of the position you picked and compared it with the evaluation results within 10 miles. The second way is if you have some requirements for your future living place and no clear idea about exact position, you can rate each quality and then the application will give you the best results for you.


## The data

Geospatial applications are all about working with data. What datasets
would you plan/like to use? If the data you'll be working with isn't
already stored in a way that you can use, how will you be storing your data?

The data is mostly from 5 datasets in OpenDataPhilly. They are in geojson data. I am still looking for if there is real-time data for transporation information.


## Technologies used


I will use underscore, jQuery, leaflet, turf to deal with the data and bootstrap for style.

Underscore and jQuery are used to make markers on the map and correspondingly show the data on the sidebar for evaluation and chart generation.

Leaflet and turf: first, when users change the data in the chart, the map will correspondingly show markers or circles(5 miles) with different color (according to evaluation level) on the maps.


## Design spec

#### User experience



example: https://phillypopemap.com/#12.54/39.9440/-75.1507, http://www.aarondennis.org/philly-crash/final/

The users are the future philly apartment/house renter or buyer. They can get most of the basic information about the residential conditions in philly to help them make comparisons and decisions.

#### Layouts and visual design


The sidebar on the left will show the evaluation results and comparsion chart (users can change the parameters on the chart to get want they expect most and the results will show on the map). On the right side next to the sidebar is the map, when users put their mouse on the map (no click) it will show the schools, transportation, crime rate, hospitals and renting price information within 10 miles of that point. On the bottom bar, they will be a users rating system, so the users can rate according to their satisfaction about the results the application provided and this can work as the reference for further users.
