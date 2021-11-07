# UFOs
Module 11 JavaScript, Bootstrap, and UFOs

## Overview of project

The purpose of this analysis is to create a website with input fields that can filter data related to UFO sightings. I used JavaScript, HTML, and CSS in order to create a functional website to display UFO sighting data. The JavaScript code allows a user to filter the sightings based on a variety of search options like Date or City.


## Results

The website displays a table of hundreds of UFO sighting events. A user can filter the sightings in five different ways: on Data, City, State, County, or Shape. In order to filter down on a specific field, a user would have to enter a string of text into at least one of the five filter fields on the left. If a user inputs something in one of the fields, the page will automatically filter out all results that don't match the search value. 

![Any_title](https://raw.githubusercontent.com/mdwilliams11/UFOs/main/ufofilter.png)


## Summary

One drawback of this new design is that the input fields are case sensitive and don't have any warning to the user. A user might get confused when their search for a sighting in the city of "El Cajon" doesn't show anything when they know there are sightings in that city in the data but it's only accessible when filtering for "el cajon".


Suggested Improvements

- A possible improvement to this page is to only accept filter values that are in the same format as the data. Users might search for a city or state with different capitalization than what the data is stored as. We could add something that returns a "please enter your search in (this) format" to help the user better navigate the page.

- The user might not know what shapes or countries to even search for. The page could include more information to help a user make their search such as the range of dates available, the counties listed, or the shapes of UFO listed.





