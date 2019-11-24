
### ![GA](https://cloud.githubusercontent.com/assets/40461/8183776/469f976e-1432-11e5-8199-6ac91363302b.png) General Assembly, Software Engineering Immersive
# Project #2: Metropolists

## Overview
Metropolists is a website that gives users the opportunity to view economic information about cities they are interested in and also compare data from different categories between two cities. Information is gathered from an external api. 
## Brief
Requirements include: 

Consume a public API – this could be anything but it must make sense for your project.

Have several components - At least one classical and one functional.

The app should include a router - with several "pages".

Include wireframes - that you designed before building the app.

Have semantically clean HTML - you make sure you write HTML that makes structural sense rather than thinking about how it might look, which is the job of CSS.

Be deployed online and accessible to the public.
## Technologies used
REACT

Bulma

CSS

HTML

Javascript

## Approach
We decided as a team to search for a open working API which had images and information we could map on. We chose the teleport public API and began wireframing the website, gave ourselves a timeframe to finish the logic aspect on the first day and styling by the final day. 

Our components for our project incluides:

An index page to run our root. 

A filter which allows uses to search cities by their names and continents. 

A navbar which routes to the pages. 

Features on the website which includes: 

Search through cities. 

Filter by continents.

Show images of city landmarks. 

A compare functions that allows you to measure which city does better at different economical categories. 

Details about city. 


## Screenshots



## Bugs 
One of the bugs we faced was we couldn't map on the array to get the data as the categories were not populated in order. We had to use a find method that works on an array for categories not in order. 

Second bug we faced was incorporating the data according to their names. Certain data didn't come with the name of the cities so we took the slug and mappeed it to get the name of cities. 

A little struggle with changing the color of the progress bars to show which city did better in each category but checked Bulma documentation for bug fix. 

Populating modal page data accurately for all cities. 
## Future features

Geographical map of each city under details. 

## Lessons learned
Using find function to work with data arrays instead of using index. 

Learning how to use Modal pages for your website. 

Creating a filter functions to handle our city data with a search feature. 


## Artwork and credit

Logo icon made by [Freepik](https://www.freepik.com/) from [www.flaticon.com](https://www.flaticon.com/).

API Documentation by Teleport: https://teleport.org/ from https://developers.teleport.org/api/
