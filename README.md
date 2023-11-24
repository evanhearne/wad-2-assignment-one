# Assignment 1 - ReactJS app.

Name: Evan Hearne

## Overview.

This repository contains an extended version of the Week 7 Labs from Web App Development 2, a module undertaken in the Computer Science course in third year at South East Technological University (Waterford Campus).

It is extended using additional endpoints, caching, search filters, toggle switch to change header colour and pagination to separate results.

### Features.
 
+ Added TV Shows Page with ability to "zoom in" to a specific show via the Details button.
+ Added Regions Page which allows user to see all the regions that TMDB knows about.
+ Added Popular Page with ability to "zoom in" to a specific actor via the Details button.
+ Added new search filter for languages in Home page.
+ Added switch toggle to change the color of the site header.
+ Added Pagination to Upcoming Page.

## Setup requirements.

```bash
npm install
npm start
```

## API endpoints.

+ TV shows - /tv
+ TV show by id = /tv/:id
+ Watch Provider Regions - /watch/providers/regions
+ Popular actors - /person/popular
+ Popular actors by id - /person/:id

## Routing.

+ /tv - displays all tv shows.
+ /tv/:id - displays a particular tv show.
+ /regions - displays all watch provider regions known by TMDB.
+ /popular - displays all popular actors.
+ /popular/:id - displays a particular actor.

## Independent learning (If relevant).

I used Pagination from [MaterialUI](https://mui.com/material-ui/react-pagination/) to assist me in adding pagination.